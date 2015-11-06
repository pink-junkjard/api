## cljs.repl.browser/repl-env



 <table border="1">
<tr>
<td>function</td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
</table>


 <samp>
(__repl-env__ & {:as opts})<br>
</samp>

---





Source docstring:

```
Create a browser-connected REPL environment.

Options:

port:           The port on which the REPL server will run. Defaults to 9000.
working-dir:    The directory where the compiled REPL client JavaScript will
                be stored. Defaults to ".repl" with a ClojureScript version
                suffix, eg. ".repl-0.0-2138".
serve-static:   Should the REPL server attempt to serve static content?
                Defaults to true.
static-dir:     List of directories to search for static content. Defaults to
                ["." "out/"].
preloaded-libs: List of namespaces that should not be sent from the REPL server
                to the browser. This may be required if the browser is already
                loading code and reloading it would cause a problem.
optimizations:  The level of optimization to use when compiling the client
                end of the REPL. Defaults to :simple.
src:            The source directory containing user-defined cljs files. Used to
                support reflection. Defaults to "src/".

```


Source code @ [github](https://github.com/clojure/clojurescript/blob/r2850/src/clj/cljs/repl/browser.clj#L256-L311):

```clj
(defn repl-env
  [& {:as opts}]
  (let [ups-deps (cljsc/get-upstream-deps (java.lang.ClassLoader/getSystemClassLoader))
        opts (assoc opts
               :ups-libs (:libs ups-deps)
               :ups-foreign-libs (:foreign-libs ups-deps))
        compiler-env (cljs.env/default-compiler-env opts)
        opts (merge (BrowserEnv.)
               {:port           9000
                :optimizations  :simple
                :working-dir    (or (:output-dir opts)
                                    (->> [".repl" (util/clojurescript-version)]
                                      (remove empty?) (string/join "-")))
                :serve-static   true
                :static-dir     (cond-> ["." "out/"]
                                  (:output-dir opts) (conj (:output-dir opts)))
                :preloaded-libs []
                :src            "src/"
                ::env/compiler  compiler-env
                :source-map     false}
               opts)]
    (cljs.env/with-compiler-env compiler-env
      (reset! preloaded-libs
        (set (concat
               (always-preload opts)
               (map str (:preloaded-libs opts)))))
      (reset! loaded-libs @preloaded-libs)
      (println "Compiling client js ...")
      (swap! browser-state
        (fn [old]
          (assoc old :client-js
            (create-client-js-file
              opts
              (io/file (:working-dir opts) "client.js")))))
      (println "Waiting for browser to connect ...")
      opts)))
```

<!--
Repo - tag - source tree - lines:

 <pre>
clojurescript @ r2850
└── src
    └── clj
        └── cljs
            └── repl
                └── <ins>[browser.clj:256-311](https://github.com/clojure/clojurescript/blob/r2850/src/clj/cljs/repl/browser.clj#L256-L311)</ins>
</pre>

-->

---



###### External doc links:

[`cljs.repl.browser/repl-env` @ crossclj](http://crossclj.info/fun/cljs.repl.browser/repl-env.html)<br>

---

 <table>
<tr><td>
<img valign="middle" align="right" width="48px" src="http://i.imgur.com/Hi20huC.png">
</td><td>
Created for the upcoming ClojureScript website.<br>
[edit here] | [learn how]
</td></tr></table>

[edit here]:https://github.com/cljsinfo/cljs-api-docs/blob/master/cljsdoc/cljs.repl.browser/repl-env.cljsdoc
[learn how]:https://github.com/cljsinfo/cljs-api-docs/wiki/cljsdoc-files

<!--

This information was too distracting to show to readers, but I'll leave it
commented here since it is helpful to:

- pretty-print the data used to generate this document
- and show how to retrieve that data



The API data for this symbol:

```clj
{:ns "cljs.repl.browser",
 :name "repl-env",
 :signature ["[& {:as opts}]"],
 :history [["+" "0.0-927"]],
 :type "function",
 :full-name-encode "cljs.repl.browser/repl-env",
 :source {:code "(defn repl-env\n  [& {:as opts}]\n  (let [ups-deps (cljsc/get-upstream-deps (java.lang.ClassLoader/getSystemClassLoader))\n        opts (assoc opts\n               :ups-libs (:libs ups-deps)\n               :ups-foreign-libs (:foreign-libs ups-deps))\n        compiler-env (cljs.env/default-compiler-env opts)\n        opts (merge (BrowserEnv.)\n               {:port           9000\n                :optimizations  :simple\n                :working-dir    (or (:output-dir opts)\n                                    (->> [\".repl\" (util/clojurescript-version)]\n                                      (remove empty?) (string/join \"-\")))\n                :serve-static   true\n                :static-dir     (cond-> [\".\" \"out/\"]\n                                  (:output-dir opts) (conj (:output-dir opts)))\n                :preloaded-libs []\n                :src            \"src/\"\n                ::env/compiler  compiler-env\n                :source-map     false}\n               opts)]\n    (cljs.env/with-compiler-env compiler-env\n      (reset! preloaded-libs\n        (set (concat\n               (always-preload opts)\n               (map str (:preloaded-libs opts)))))\n      (reset! loaded-libs @preloaded-libs)\n      (println \"Compiling client js ...\")\n      (swap! browser-state\n        (fn [old]\n          (assoc old :client-js\n            (create-client-js-file\n              opts\n              (io/file (:working-dir opts) \"client.js\")))))\n      (println \"Waiting for browser to connect ...\")\n      opts)))",
          :title "Source code",
          :repo "clojurescript",
          :tag "r2850",
          :filename "src/clj/cljs/repl/browser.clj",
          :lines [256 311]},
 :full-name "cljs.repl.browser/repl-env",
 :docstring "Create a browser-connected REPL environment.\n\nOptions:\n\nport:           The port on which the REPL server will run. Defaults to 9000.\nworking-dir:    The directory where the compiled REPL client JavaScript will\n                be stored. Defaults to \".repl\" with a ClojureScript version\n                suffix, eg. \".repl-0.0-2138\".\nserve-static:   Should the REPL server attempt to serve static content?\n                Defaults to true.\nstatic-dir:     List of directories to search for static content. Defaults to\n                [\".\" \"out/\"].\npreloaded-libs: List of namespaces that should not be sent from the REPL server\n                to the browser. This may be required if the browser is already\n                loading code and reloading it would cause a problem.\noptimizations:  The level of optimization to use when compiling the client\n                end of the REPL. Defaults to :simple.\nsrc:            The source directory containing user-defined cljs files. Used to\n                support reflection. Defaults to \"src/\".\n"}

```

Retrieve the API data for this symbol:

```clj
;; from Clojure REPL
(require '[clojure.edn :as edn])
(-> (slurp "https://raw.githubusercontent.com/cljsinfo/cljs-api-docs/catalog/cljs-api.edn")
    (edn/read-string)
    (get-in [:symbols "cljs.repl.browser/repl-env"]))
```

-->