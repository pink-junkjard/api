## cljs.core/interpose



 <table border="1">
<tr>
<td>function</td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
<td>
[<img height="24px" valign="middle" src="http://i.imgur.com/1GjPKvB.png"> <samp>clojure.core/interpose</samp>](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/interpose)
</td>
</tr>
</table>


 <samp>
(__interpose__ sep coll)<br>
</samp>

---

Returns a lazy seq of the elements of `coll` separated by `sep`.



---


###### See Also:

[`cljs.core/interleave`](../cljs.core/interleave.md)<br>
[`clojure.string/join`](../clojure.string/join.md)<br>

---


Source docstring:

```
Returns a lazy seq of the elements of coll separated by sep
```


Source code @ [github](https://github.com/clojure/clojurescript/blob/r2850/src/cljs/cljs/core.cljs#L3916-L3933):

```clj
(defn interpose
  ([sep]
    (fn [rf]
      (let [started (volatile! false)]
        (fn
          ([] (rf))
          ([result] (rf result))
          ([result input]
            (if @started
              (let [sepr (rf result sep)]
                (if (reduced? sepr)
                  sepr
                  (rf sepr input)))
              (do
                (vreset! started true)
                (rf result input))))))))
  ([sep coll] (drop 1 (interleave (repeat sep) coll))))
```

<!--
Repo - tag - source tree - lines:

 <pre>
clojurescript @ r2850
└── src
    └── cljs
        └── cljs
            └── <ins>[core.cljs:3916-3933](https://github.com/clojure/clojurescript/blob/r2850/src/cljs/cljs/core.cljs#L3916-L3933)</ins>
</pre>

-->

---



###### External doc links:

[`clojure.core/interpose` @ clojuredocs](http://clojuredocs.org/clojure.core/interpose)<br>
[`clojure.core/interpose` @ grimoire](http://conj.io/store/v1/org.clojure/clojure/1.7.0-beta3/clj/clojure.core/interpose/)<br>
[`clojure.core/interpose` @ crossclj](http://crossclj.info/fun/clojure.core/interpose.html)<br>
[`cljs.core/interpose` @ crossclj](http://crossclj.info/fun/cljs.core.cljs/interpose.html)<br>

---

 <table>
<tr><td>
<img valign="middle" align="right" width="48px" src="http://i.imgur.com/Hi20huC.png">
</td><td>
Created for the upcoming ClojureScript website.<br>
[edit here] | [learn how]
</td></tr></table>

[edit here]:https://github.com/cljsinfo/cljs-api-docs/blob/master/cljsdoc/cljs.core/interpose.cljsdoc
[learn how]:https://github.com/cljsinfo/cljs-api-docs/wiki/cljsdoc-files

<!--

This information was too distracting to show to readers, but I'll leave it
commented here since it is helpful to:

- pretty-print the data used to generate this document
- and show how to retrieve that data



The API data for this symbol:

```clj
{:description "Returns a lazy seq of the elements of `coll` separated by `sep`.",
 :ns "cljs.core",
 :name "interpose",
 :signature ["[sep coll]"],
 :history [["+" "0.0-927"]],
 :type "function",
 :related ["cljs.core/interleave" "clojure.string/join"],
 :full-name-encode "cljs.core/interpose",
 :source {:code "(defn interpose\n  ([sep]\n    (fn [rf]\n      (let [started (volatile! false)]\n        (fn\n          ([] (rf))\n          ([result] (rf result))\n          ([result input]\n            (if @started\n              (let [sepr (rf result sep)]\n                (if (reduced? sepr)\n                  sepr\n                  (rf sepr input)))\n              (do\n                (vreset! started true)\n                (rf result input))))))))\n  ([sep coll] (drop 1 (interleave (repeat sep) coll))))",
          :title "Source code",
          :repo "clojurescript",
          :tag "r2850",
          :filename "src/cljs/cljs/core.cljs",
          :lines [3916 3933]},
 :full-name "cljs.core/interpose",
 :clj-symbol "clojure.core/interpose",
 :docstring "Returns a lazy seq of the elements of coll separated by sep"}

```

Retrieve the API data for this symbol:

```clj
;; from Clojure REPL
(require '[clojure.edn :as edn])
(-> (slurp "https://raw.githubusercontent.com/cljsinfo/cljs-api-docs/catalog/cljs-api.edn")
    (edn/read-string)
    (get-in [:symbols "cljs.core/interpose"]))
```

-->