## def

_known as "define"_


 <table border="1">
<tr>
<td>special form</td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
<td>
[<img height="24px" valign="middle" src="http://i.imgur.com/1GjPKvB.png"> <samp>clojure.core/def</samp>](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/def)
</td>
</tr>
</table>


 <samp>
(__def__ symbol)<br>
</samp>
 <samp>
(__def__ symbol init)<br>
</samp>
 <samp>
(__def__ symbol doc-string init)<br>
</samp>

---

Creates a global variable with the name of `symbol` and a namespace of the
current namespace.

If `init` is supplied, it is evaluated and the result is assigned to `symbol`.

`doc-string` is an optional documentation string.

`def` is one of ClojureScript's [special forms](http://clojure.org/special_forms)
and is used by many macros to define common elements (ie: `defn`, `defmacro`,
etc).

Supported metadata:

- `^:private boolean` - make non-accessible from other namespaces
- `^:dynamic boolean` - make [dynamically bindable][doc:cljs.core/binding] (usually named with [`earmuffs`][doc:syntax/earmuffs])
- `^:const boolean` - prevents redef and allows it to be used in [`case`][doc:cljs.core/case].
- `^:jsdoc [""]` - vector of JSDoc Tags for [Google Closure][closure-jsdoc] or [standard][other-jsdoc].
- `^:test (fn [] (assert ...))` - allows function to be tested with [`test`][doc:cljs.core/test].
- `^:doc ""` - doc-string (prefer the use of the `(def symbol doc-string init)`)

[closure-jsdoc]:https://developers.google.com/closure/compiler/docs/js-for-compiler?hl=en#tags
[other-jsdoc]:http://usejsdoc.org/#block-tags

Compiler will also add metadata:

- `:ns`
- `:name`
- `:file`
- `:line`, `:end-line`
- `:column`, `:end-column`
- `:source`
- `:arglists`

[doc:cljs.core/binding]:../cljs.core/binding.md
[doc:syntax/earmuffs]:../syntax/earmuffs.md
[doc:cljs.core/case]:../cljs.core/case.md
[doc:cljs.core/test]:../cljs.core/test.md

---

###### Examples:

```clj
(def a)
a
;;=> nil

(def b 42)
b
;;=> 42

(def c "an optional docstring" 42)
c
;;=> 42
```



---

###### See Also:

[`cljs.core/defn`](../cljs.core/defn.md)<br>
[`cljs.core/fn`](../cljs.core/fn.md)<br>
[`cljs.core/defmacro`](../cljs.core/defmacro.md)<br>
[`cljs.core/defmulti`](../cljs.core/defmulti.md)<br>

---




Parser code @ [github](https://github.com/clojure/clojurescript/blob/r2850/src/clj/cljs/analyzer.clj#L671-L781):

```clj
(defmethod parse 'def
  [op env form name _]
  (let [pfn (fn
              ([_ sym] {:sym sym})
              ([_ sym init] {:sym sym :init init})
              ([_ sym doc init] {:sym sym :doc doc :init init}))
        args (apply pfn form)
        sym (:sym args)
        sym-meta (meta sym)
        tag (-> sym meta :tag)
        protocol (-> sym meta :protocol)
        dynamic (-> sym meta :dynamic)
        ns-name (-> env :ns :name)
        locals (:locals env)]
    (when (namespace sym)
      (throw (error env "Can't def ns-qualified name")))
    (when-let [doc (:doc args)]
      (when-not (string? doc)
        (throw (error env "Too many arguments to def"))))
    (when-let [v (get-in @env/*compiler* [::namespaces ns-name :defs sym])]
      (when (and (not *allow-redef*)
                 (not (:declared v))
                 (not (:declared sym-meta))
                 (= (:file v) *cljs-file*)
                 (not= "<cljs repl>" *cljs-file*))
        (warning :redef-in-file env {:sym sym :line (:line v)})))
    (let [env (if (or (and (not= ns-name 'cljs.core)
                           (core-name? env sym))
                      (get-in @env/*compiler* [::namespaces ns-name :uses sym]))
                (let [ev (resolve-existing-var (dissoc env :locals) sym)]
                  (warning :redef env {:sym sym :ns (:ns ev) :ns-name ns-name})
                  (swap! env/*compiler* update-in [::namespaces ns-name :excludes] conj sym)
                  (update-in env [:ns :excludes] conj sym))
                env)
          var-name (:name (resolve-var (dissoc env :locals) sym))
          init-expr (when (contains? args :init)
                      (swap! env/*compiler* assoc-in [::namespaces ns-name :defs sym]
                        (merge
                          {:name var-name}
                          sym-meta
                          (when dynamic {:dynamic true})
                          (source-info var-name env)))
                      (disallowing-recur
                        (analyze (assoc env :context :expr) (:init args) sym)))
          fn-var? (and init-expr (= (:op init-expr) :fn))
          tag (if fn-var?
                (or (:ret-tag init-expr) tag)
                tag)
          export-as (when-let [export-val (-> sym meta :export)]
                      (if (= true export-val) var-name export-val))
          doc (or (:doc args) (-> sym meta :doc))]
      (when-let [v (get-in @env/*compiler* [::namespaces ns-name :defs sym])]
        (when (and (not (-> sym meta :declared))
                   (and (:fn-var v) (not fn-var?)))
          (warning :fn-var env {:ns-name ns-name :sym sym})))
      (swap! env/*compiler* assoc-in [::namespaces ns-name :defs sym]
        (merge 
          {:name var-name}
          ;; elide test metadata, as it includes non-valid EDN - David
          (cond-> sym-meta
            :test (-> (dissoc :test) (assoc :test true)))
          (when doc {:doc doc})
          (when dynamic {:dynamic true})
          (source-info var-name env)
          ;; the protocol a protocol fn belongs to
          (when protocol
            {:protocol protocol})
          ;; symbol for reified protocol
          (when-let [protocol-symbol (-> sym meta :protocol-symbol)]
            {:protocol-symbol protocol-symbol
             :info (-> protocol-symbol meta :protocol-info)
             :impls #{}})
          (when fn-var?
            (let [params (map #(vec (map :name (:params %))) (:methods init-expr))]
              {:fn-var true
               ;; protocol implementation context
               :protocol-impl (:protocol-impl init-expr)
               ;; inline protocol implementation context
               :protocol-inline (:protocol-inline init-expr)
               :variadic (:variadic init-expr)
               :max-fixed-arity (:max-fixed-arity init-expr)
               :method-params params
               :arglists (:arglists sym-meta)
               :arglists-meta (doall (map meta (:arglists sym-meta)))
               :methods (map (fn [method]
                               (let [tag (infer-tag env (assoc method :op :method))]
                                 (cond-> (select-keys method
                                           [:max-fixed-arity :variadic])
                                   tag (assoc :tag tag))))
                          (:methods init-expr))}) )
          (when (and fn-var? tag)
            {:ret-tag tag})))
      (merge {:env env :op :def :form form
              :name var-name
              :var (assoc
                     (analyze
                       (-> env (dissoc :locals)
                         (assoc :context :expr)
                         (assoc :def-var true))
                       sym)
                     :op :var)
              :doc doc :init init-expr}
        (when-let [test (:test sym-meta)]
          {:test (analyze (assoc env :context :expr) test)})
        (when tag
          (if fn-var?
            {:ret-tag tag}
            {:tag tag}))
        (when dynamic {:dynamic true})
        (when export-as {:export export-as})
        (when init-expr {:children [init-expr]})))))
```

<!--
Repo - tag - source tree - lines:

 <pre>
clojurescript @ r2850
└── src
    └── clj
        └── cljs
            └── <ins>[analyzer.clj:671-781](https://github.com/clojure/clojurescript/blob/r2850/src/clj/cljs/analyzer.clj#L671-L781)</ins>
</pre>

-->

---



###### External doc links:

[`clojure.core/def` @ clojuredocs](http://clojuredocs.org/clojure.core/def)<br>
[`clojure.core/def` @ grimoire](http://conj.io/store/v1/org.clojure/clojure/1.7.0-beta3/clj/clojure.core/def/)<br>
[`clojure.core/def` @ crossclj](http://crossclj.info/fun/clojure.core/def.html)<br>

---

 <table>
<tr><td>
<img valign="middle" align="right" width="48px" src="http://i.imgur.com/Hi20huC.png">
</td><td>
Created for the upcoming ClojureScript website.<br>
[edit here] | [learn how]
</td></tr></table>

[edit here]:https://github.com/cljsinfo/cljs-api-docs/blob/master/cljsdoc/special/def.cljsdoc
[learn how]:https://github.com/cljsinfo/cljs-api-docs/wiki/cljsdoc-files

<!--

This information was too distracting to show to readers, but I'll leave it
commented here since it is helpful to:

- pretty-print the data used to generate this document
- and show how to retrieve that data



The API data for this symbol:

```clj
{:description "Creates a global variable with the name of `symbol` and a namespace of the\ncurrent namespace.\n\nIf `init` is supplied, it is evaluated and the result is assigned to `symbol`.\n\n`doc-string` is an optional documentation string.\n\n`def` is one of ClojureScript's [special forms](http://clojure.org/special_forms)\nand is used by many macros to define common elements (ie: `defn`, `defmacro`,\netc).\n\nSupported metadata:\n\n- `^:private boolean` - make non-accessible from other namespaces\n- `^:dynamic boolean` - make [dynamically bindable][doc:cljs.core/binding] (usually named with [doc:syntax/earmuffs])\n- `^:const boolean` - prevents redef and allows it to be used in [doc:cljs.core/case].\n- `^:jsdoc [\"\"]` - vector of JSDoc Tags for [Google Closure][closure-jsdoc] or [standard][other-jsdoc].\n- `^:test (fn [] (assert ...))` - allows function to be tested with [doc:cljs.core/test].\n- `^:doc \"\"` - doc-string (prefer the use of the `(def symbol doc-string init)`)\n\n[closure-jsdoc]:https://developers.google.com/closure/compiler/docs/js-for-compiler?hl=en#tags\n[other-jsdoc]:http://usejsdoc.org/#block-tags\n\nCompiler will also add metadata:\n\n- `:ns`\n- `:name`\n- `:file`\n- `:line`, `:end-line`\n- `:column`, `:end-column`\n- `:source`\n- `:arglists`",
 :ns "special",
 :name "def",
 :signature ["[symbol]" "[symbol init]" "[symbol doc-string init]"],
 :history [["+" "0.0-927"]],
 :type "special form",
 :related ["cljs.core/defn"
           "cljs.core/fn"
           "cljs.core/defmacro"
           "cljs.core/defmulti"],
 :full-name-encode "special/def",
 :source {:code "(defmethod parse 'def\n  [op env form name _]\n  (let [pfn (fn\n              ([_ sym] {:sym sym})\n              ([_ sym init] {:sym sym :init init})\n              ([_ sym doc init] {:sym sym :doc doc :init init}))\n        args (apply pfn form)\n        sym (:sym args)\n        sym-meta (meta sym)\n        tag (-> sym meta :tag)\n        protocol (-> sym meta :protocol)\n        dynamic (-> sym meta :dynamic)\n        ns-name (-> env :ns :name)\n        locals (:locals env)]\n    (when (namespace sym)\n      (throw (error env \"Can't def ns-qualified name\")))\n    (when-let [doc (:doc args)]\n      (when-not (string? doc)\n        (throw (error env \"Too many arguments to def\"))))\n    (when-let [v (get-in @env/*compiler* [::namespaces ns-name :defs sym])]\n      (when (and (not *allow-redef*)\n                 (not (:declared v))\n                 (not (:declared sym-meta))\n                 (= (:file v) *cljs-file*)\n                 (not= \"<cljs repl>\" *cljs-file*))\n        (warning :redef-in-file env {:sym sym :line (:line v)})))\n    (let [env (if (or (and (not= ns-name 'cljs.core)\n                           (core-name? env sym))\n                      (get-in @env/*compiler* [::namespaces ns-name :uses sym]))\n                (let [ev (resolve-existing-var (dissoc env :locals) sym)]\n                  (warning :redef env {:sym sym :ns (:ns ev) :ns-name ns-name})\n                  (swap! env/*compiler* update-in [::namespaces ns-name :excludes] conj sym)\n                  (update-in env [:ns :excludes] conj sym))\n                env)\n          var-name (:name (resolve-var (dissoc env :locals) sym))\n          init-expr (when (contains? args :init)\n                      (swap! env/*compiler* assoc-in [::namespaces ns-name :defs sym]\n                        (merge\n                          {:name var-name}\n                          sym-meta\n                          (when dynamic {:dynamic true})\n                          (source-info var-name env)))\n                      (disallowing-recur\n                        (analyze (assoc env :context :expr) (:init args) sym)))\n          fn-var? (and init-expr (= (:op init-expr) :fn))\n          tag (if fn-var?\n                (or (:ret-tag init-expr) tag)\n                tag)\n          export-as (when-let [export-val (-> sym meta :export)]\n                      (if (= true export-val) var-name export-val))\n          doc (or (:doc args) (-> sym meta :doc))]\n      (when-let [v (get-in @env/*compiler* [::namespaces ns-name :defs sym])]\n        (when (and (not (-> sym meta :declared))\n                   (and (:fn-var v) (not fn-var?)))\n          (warning :fn-var env {:ns-name ns-name :sym sym})))\n      (swap! env/*compiler* assoc-in [::namespaces ns-name :defs sym]\n        (merge \n          {:name var-name}\n          ;; elide test metadata, as it includes non-valid EDN - David\n          (cond-> sym-meta\n            :test (-> (dissoc :test) (assoc :test true)))\n          (when doc {:doc doc})\n          (when dynamic {:dynamic true})\n          (source-info var-name env)\n          ;; the protocol a protocol fn belongs to\n          (when protocol\n            {:protocol protocol})\n          ;; symbol for reified protocol\n          (when-let [protocol-symbol (-> sym meta :protocol-symbol)]\n            {:protocol-symbol protocol-symbol\n             :info (-> protocol-symbol meta :protocol-info)\n             :impls #{}})\n          (when fn-var?\n            (let [params (map #(vec (map :name (:params %))) (:methods init-expr))]\n              {:fn-var true\n               ;; protocol implementation context\n               :protocol-impl (:protocol-impl init-expr)\n               ;; inline protocol implementation context\n               :protocol-inline (:protocol-inline init-expr)\n               :variadic (:variadic init-expr)\n               :max-fixed-arity (:max-fixed-arity init-expr)\n               :method-params params\n               :arglists (:arglists sym-meta)\n               :arglists-meta (doall (map meta (:arglists sym-meta)))\n               :methods (map (fn [method]\n                               (let [tag (infer-tag env (assoc method :op :method))]\n                                 (cond-> (select-keys method\n                                           [:max-fixed-arity :variadic])\n                                   tag (assoc :tag tag))))\n                          (:methods init-expr))}) )\n          (when (and fn-var? tag)\n            {:ret-tag tag})))\n      (merge {:env env :op :def :form form\n              :name var-name\n              :var (assoc\n                     (analyze\n                       (-> env (dissoc :locals)\n                         (assoc :context :expr)\n                         (assoc :def-var true))\n                       sym)\n                     :op :var)\n              :doc doc :init init-expr}\n        (when-let [test (:test sym-meta)]\n          {:test (analyze (assoc env :context :expr) test)})\n        (when tag\n          (if fn-var?\n            {:ret-tag tag}\n            {:tag tag}))\n        (when dynamic {:dynamic true})\n        (when export-as {:export export-as})\n        (when init-expr {:children [init-expr]})))))",
          :title "Parser code",
          :repo "clojurescript",
          :tag "r2850",
          :filename "src/clj/cljs/analyzer.clj",
          :lines [671 781]},
 :examples [{:id "a5f898",
             :content "```clj\n(def a)\na\n;;=> nil\n\n(def b 42)\nb\n;;=> 42\n\n(def c \"an optional docstring\" 42)\nc\n;;=> 42\n```"}],
 :known-as "define",
 :full-name "special/def",
 :clj-symbol "clojure.core/def"}

```

Retrieve the API data for this symbol:

```clj
;; from Clojure REPL
(require '[clojure.edn :as edn])
(-> (slurp "https://raw.githubusercontent.com/cljsinfo/cljs-api-docs/catalog/cljs-api.edn")
    (edn/read-string)
    (get-in [:symbols "special/def"]))
```

-->