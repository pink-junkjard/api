## <img width="48px" valign="middle" src="http://i.imgur.com/Hi20huC.png"> special/new

 <table border="1">
<tr>
<td>special form</td>
<td><a href="https://github.com/cljsinfo/api-refs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
<td>
[<img height="24px" valign="middle" src="http://i.imgur.com/1GjPKvB.png"> <samp>clojure.core/new</samp>](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/new)
</td>
</tr>
</table>

 <samp>
</samp>

```
(no docstring)
```

---

 <pre>
clojurescript @ r1011
└── src
    └── clj
        └── cljs
            └── <ins>[compiler.clj:816-822](https://github.com/clojure/clojurescript/blob/r1011/src/clj/cljs/compiler.clj#L816-L822)</ins>
</pre>

```clj
(defmethod parse 'new
  [_ env [_ ctor & args] _]
  (disallowing-recur
   (let [enve (assoc env :context :expr)
         ctorexpr (analyze enve ctor)
         argexprs (vec (map #(analyze enve %) args))]
     {:env env :op :new :ctor ctorexpr :args argexprs :children (conj argexprs ctorexpr)})))
```


---

```clj
{:full-name "special/new",
 :ns "special",
 :name "new",
 :type "special form",
 :source {:code "(defmethod parse 'new\n  [_ env [_ ctor & args] _]\n  (disallowing-recur\n   (let [enve (assoc env :context :expr)\n         ctorexpr (analyze enve ctor)\n         argexprs (vec (map #(analyze enve %) args))]\n     {:env env :op :new :ctor ctorexpr :args argexprs :children (conj argexprs ctorexpr)})))",
          :filename "clojurescript/src/clj/cljs/compiler.clj",
          :lines [816 822],
          :link "https://github.com/clojure/clojurescript/blob/r1011/src/clj/cljs/compiler.clj#L816-L822"},
 :full-name-encode "special_new",
 :clj-symbol "clojure.core/new",
 :history [["+" "0.0-927"]]}

```