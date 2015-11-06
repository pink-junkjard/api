## cljs.test/async?



 <table border="1">
<tr>
<td>function</td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2814"><img valign="middle" alt="[+] 0.0-2814" title="Added in 0.0-2814" src="https://img.shields.io/badge/+-0.0--2814-lightgrey.svg"></a> </td>
</tr>
</table>


 <samp>
(__async?__ x)<br>
</samp>

---





Source docstring:

```
Returns whether x implements IAsyncTest.
```


Source code @ [github](https://github.com/clojure/clojurescript/blob/r2850/src/cljs/cljs/test.cljs#L403-L406):

```clj
(defn async?
  [x]
  (satisfies? IAsyncTest x))
```

<!--
Repo - tag - source tree - lines:

 <pre>
clojurescript @ r2850
└── src
    └── cljs
        └── cljs
            └── <ins>[test.cljs:403-406](https://github.com/clojure/clojurescript/blob/r2850/src/cljs/cljs/test.cljs#L403-L406)</ins>
</pre>

-->

---



###### External doc links:

[`cljs.test/async?` @ crossclj](http://crossclj.info/fun/cljs.test.cljs/async%3F.html)<br>

---

 <table>
<tr><td>
<img valign="middle" align="right" width="48px" src="http://i.imgur.com/Hi20huC.png">
</td><td>
Created for the upcoming ClojureScript website.<br>
[edit here] | [learn how]
</td></tr></table>

[edit here]:https://github.com/cljsinfo/cljs-api-docs/blob/master/cljsdoc/cljs.test/asyncQMARK.cljsdoc
[learn how]:https://github.com/cljsinfo/cljs-api-docs/wiki/cljsdoc-files

<!--

This information was too distracting to show to readers, but I'll leave it
commented here since it is helpful to:

- pretty-print the data used to generate this document
- and show how to retrieve that data



The API data for this symbol:

```clj
{:ns "cljs.test",
 :name "async?",
 :signature ["[x]"],
 :history [["+" "0.0-2814"]],
 :type "function",
 :full-name-encode "cljs.test/asyncQMARK",
 :source {:code "(defn async?\n  [x]\n  (satisfies? IAsyncTest x))",
          :title "Source code",
          :repo "clojurescript",
          :tag "r2850",
          :filename "src/cljs/cljs/test.cljs",
          :lines [403 406]},
 :full-name "cljs.test/async?",
 :docstring "Returns whether x implements IAsyncTest."}

```

Retrieve the API data for this symbol:

```clj
;; from Clojure REPL
(require '[clojure.edn :as edn])
(-> (slurp "https://raw.githubusercontent.com/cljsinfo/cljs-api-docs/catalog/cljs-api.edn")
    (edn/read-string)
    (get-in [:symbols "cljs.test/async?"]))
```

-->