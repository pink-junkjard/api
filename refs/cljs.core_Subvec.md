## <img width="48px" valign="middle" src="http://i.imgur.com/Hi20huC.png"> cljs.core/Subvec

 <table border="1">
<tr>
<td>type</td>
<td><a href="https://github.com/cljsinfo/api-refs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
</table>

 <samp>
(__Subvec.__ meta v start end)<br>
</samp>

```
(no docstring)
```

---

 <pre>
clojurescript @ r1011
└── src
    └── cljs
        └── cljs
            └── <ins>[core.cljs:2208-2278](https://github.com/clojure/clojurescript/blob/r1011/src/cljs/cljs/core.cljs#L2208-L2278)</ins>
</pre>

```clj
(deftype Subvec [meta v start end]
  IWithMeta
  (-with-meta [coll meta] (Subvec. meta v start end))

  IMeta
  (-meta [coll] meta)

  IStack
  (-peek [coll]
    (-nth v (dec end)))
  (-pop [coll]
    (if (= start end)
      (throw (js/Error. "Can't pop empty vector"))
      (Subvec. meta v start (dec end))))

  ICollection
  (-conj [coll o]
    (Subvec. meta (-assoc-n v end o) start (inc end)))

  IEmptyableCollection
  (-empty [coll] (with-meta cljs.core.Vector/EMPTY meta))

  ISequential
  IEquiv
  (-equiv [coll other] (equiv-sequential coll other))

  IHash
  (-hash [coll] (hash-coll coll))

  ISeqable
  (-seq [coll]
    (let [subvec-seq (fn subvec-seq [i]
                       (when-not (= i end)
                         (cons (-nth v i)
                               (lazy-seq
                                (subvec-seq (inc i))))))]
      (subvec-seq start)))

  ICounted
  (-count [coll] (- end start))

  IIndexed
  (-nth [coll n]
    (-nth v (+ start n)))
  (-nth [coll n not-found]
    (-nth v (+ start n) not-found))

  ILookup
  (-lookup [coll k] (-nth coll k nil))
  (-lookup [coll k not-found] (-nth coll k not-found))

  IAssociative
  (-assoc [coll key val]
    (let [v-pos (+ start key)]
      (Subvec. meta (-assoc v v-pos val)
               start (max end (inc v-pos)))))

  IVector
  (-assoc-n [coll n val] (-assoc coll n val))

  IReduce
  (-reduce [coll f]
    (ci-reduce coll f))
  (-reduce [coll f start]
    (ci-reduce coll f start))

  IFn
  (-invoke [coll k]
    (-lookup coll k))
  (-invoke [coll k not-found]
    (-lookup coll k not-found)))
```


---

```clj
{:full-name "cljs.core/Subvec",
 :ns "cljs.core",
 :name "Subvec",
 :type "type",
 :signature ["[meta v start end]"],
 :source {:code "(deftype Subvec [meta v start end]\n  IWithMeta\n  (-with-meta [coll meta] (Subvec. meta v start end))\n\n  IMeta\n  (-meta [coll] meta)\n\n  IStack\n  (-peek [coll]\n    (-nth v (dec end)))\n  (-pop [coll]\n    (if (= start end)\n      (throw (js/Error. \"Can't pop empty vector\"))\n      (Subvec. meta v start (dec end))))\n\n  ICollection\n  (-conj [coll o]\n    (Subvec. meta (-assoc-n v end o) start (inc end)))\n\n  IEmptyableCollection\n  (-empty [coll] (with-meta cljs.core.Vector/EMPTY meta))\n\n  ISequential\n  IEquiv\n  (-equiv [coll other] (equiv-sequential coll other))\n\n  IHash\n  (-hash [coll] (hash-coll coll))\n\n  ISeqable\n  (-seq [coll]\n    (let [subvec-seq (fn subvec-seq [i]\n                       (when-not (= i end)\n                         (cons (-nth v i)\n                               (lazy-seq\n                                (subvec-seq (inc i))))))]\n      (subvec-seq start)))\n\n  ICounted\n  (-count [coll] (- end start))\n\n  IIndexed\n  (-nth [coll n]\n    (-nth v (+ start n)))\n  (-nth [coll n not-found]\n    (-nth v (+ start n) not-found))\n\n  ILookup\n  (-lookup [coll k] (-nth coll k nil))\n  (-lookup [coll k not-found] (-nth coll k not-found))\n\n  IAssociative\n  (-assoc [coll key val]\n    (let [v-pos (+ start key)]\n      (Subvec. meta (-assoc v v-pos val)\n               start (max end (inc v-pos)))))\n\n  IVector\n  (-assoc-n [coll n val] (-assoc coll n val))\n\n  IReduce\n  (-reduce [coll f]\n    (ci-reduce coll f))\n  (-reduce [coll f start]\n    (ci-reduce coll f start))\n\n  IFn\n  (-invoke [coll k]\n    (-lookup coll k))\n  (-invoke [coll k not-found]\n    (-lookup coll k not-found)))",
          :filename "clojurescript/src/cljs/cljs/core.cljs",
          :lines [2208 2278],
          :link "https://github.com/clojure/clojurescript/blob/r1011/src/cljs/cljs/core.cljs#L2208-L2278"},
 :full-name-encode "cljs.core_Subvec",
 :history [["+" "0.0-927"]]}

```