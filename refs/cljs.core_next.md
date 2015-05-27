## <img width="48px" valign="middle" src="http://i.imgur.com/Hi20huC.png"> cljs.core/next

 <table border="1">
<tr>
<td>function</td>
<td><a href="https://github.com/cljsinfo/api-refs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
<td>
[<img height="24px" valign="middle" src="http://i.imgur.com/1GjPKvB.png"> <samp>clojure.core/next</samp>](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/next)
</td>
</tr>
</table>

 <samp>
(__next__ coll)<br>
</samp>

```
Returns a seq of the items after the first. Calls seq on its
argument.  If there are no more items, returns nil
```

---

 <pre>
clojurescript @ r1011
└── src
    └── cljs
        └── cljs
            └── <ins>[core.cljs:425-430](https://github.com/clojure/clojurescript/blob/r1011/src/cljs/cljs/core.cljs#L425-L430)</ins>
</pre>

```clj
(defn next
  [coll]
  (when coll
    (seq (rest coll))))
```


---

```clj
{:ns "cljs.core",
 :name "next",
 :signature ["[coll]"],
 :history [["+" "0.0-927"]],
 :type "function",
 :full-name-encode "cljs.core_next",
 :source {:code "(defn next\n  [coll]\n  (when coll\n    (seq (rest coll))))",
          :filename "clojurescript/src/cljs/cljs/core.cljs",
          :lines [425 430],
          :link "https://github.com/clojure/clojurescript/blob/r1011/src/cljs/cljs/core.cljs#L425-L430"},
 :full-name "cljs.core/next",
 :clj-symbol "clojure.core/next",
 :docstring "Returns a seq of the items after the first. Calls seq on its\nargument.  If there are no more items, returns nil"}

```