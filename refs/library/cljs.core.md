## cljs.core

 <table border="1">
<tr>
<td>namespace</td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
<td>
[<img height="24px" valign="middle" src="http://i.imgur.com/1GjPKvB.png"> <samp>clojure.core</samp>](http://clojure.github.io/clojure/branch-master/clojure.core-api.html)
</td>
</tr>
</table>

This is the core library of ClojureScript, which builds on the Special Forms to
complete the language's fundamental constructs. It also provides a slew of core
operations for managing state, creating/manipulating/querying data structures,
interop with JS, many predicates, etc.

###### Some side notes:

- All of the core library can be referenced without the `cljs.core/` qualification.
- Operations listed as `function/macro` are flexible and can be used as macros
  or functions when appropriate.  [details here](https://github.com/clojure/clojurescript/wiki/Differences-from-Clojure#macros)
- You can use this reference to explore the core types and protocols used to
  implement many of the operations in this core library.
- We are currently only listing the &quot;ClojureScript JVM&quot; implementations here.
  The &quot;ClojureScript JS&quot; macro implementations are not listed here, but their
  API is identical of course.



---


###### Public Symbols:

 <table>
<thead><tr>
<th>=</th>
<th>Name</th>
<th>Type</th>
<th>History</th>
</tr></thead>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/*)</td>
<td><samp>[\*](../cljs.core/STAR.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/*1)</td>
<td><samp>[\*1](../cljs.core/STAR1.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/*2)</td>
<td><samp>[\*2](../cljs.core/STAR2.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/*3)</td>
<td><samp>[\*3](../cljs.core/STAR3.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/*clojure-version*)</td>
<td><samp>[\*clojurescript-version\*](../cljs.core/STARclojurescript-versionSTAR.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2014"><img valign="middle" alt="[+] 0.0-2014" title="Added in 0.0-2014" src="https://img.shields.io/badge/+-0.0--2014-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/*e)</td>
<td><samp>[\*e](../cljs.core/STARe.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2814"><img valign="middle" alt="[+] 0.0-2814" title="Added in 0.0-2814" src="https://img.shields.io/badge/+-0.0--2814-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/*flush-on-newline*)</td>
<td><samp>[\*flush-on-newline\*](../cljs.core/STARflush-on-newlineSTAR.md)</samp></td>
<td><samp>dynamic var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[\*loaded-libs\*](../cljs.core/STARloaded-libsSTAR.md)</samp></td>
<td><samp>dynamic var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2655"><img valign="middle" alt="[+] 0.0-2655" title="Added in 0.0-2655" src="https://img.shields.io/badge/+-0.0--2655-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[\*main-cli-fn\*](../cljs.core/STARmain-cli-fnSTAR.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/*print-dup*)</td>
<td><samp>[\*print-dup\*](../cljs.core/STARprint-dupSTAR.md)</samp></td>
<td><samp>dynamic var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[\*print-fn\*](../cljs.core/STARprint-fnSTAR.md)</samp></td>
<td><samp>dynamic var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/*print-length*)</td>
<td><samp>[\*print-length\*](../cljs.core/STARprint-lengthSTAR.md)</samp></td>
<td><samp>dynamic var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2060"><img valign="middle" alt="[+] 0.0-2060" title="Added in 0.0-2060" src="https://img.shields.io/badge/+-0.0--2060-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/*print-level*)</td>
<td><samp>[\*print-level\*](../cljs.core/STARprint-levelSTAR.md)</samp></td>
<td><samp>dynamic var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2120"><img valign="middle" alt="[+] 0.0-2120" title="Added in 0.0-2120" src="https://img.shields.io/badge/+-0.0--2120-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/*print-meta*)</td>
<td><samp>[\*print-meta\*](../cljs.core/STARprint-metaSTAR.md)</samp></td>
<td><samp>dynamic var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[\*print-newline\*](../cljs.core/STARprint-newlineSTAR.md)</samp></td>
<td><samp>dynamic var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2060"><img valign="middle" alt="[+] 0.0-2060" title="Added in 0.0-2060" src="https://img.shields.io/badge/+-0.0--2060-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/*print-readably*)</td>
<td><samp>[\*print-readably\*](../cljs.core/STARprint-readablySTAR.md)</samp></td>
<td><samp>dynamic var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[\*unchecked-if\*](../cljs.core/STARunchecked-ifSTAR.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/+)</td>
<td><samp>[+](../cljs.core/PLUS.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/-)</td>
<td><samp>[-](../cljs.core/-.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/-%3E) <samp>→</samp></td>
<td><samp>[->](../cljs.core/-GT.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/-%3E%3E) <samp>→</samp></td>
<td><samp>[->>](../cljs.core/-GTGT.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/..) <samp>→</samp></td>
<td><samp>[..](../cljs.core/DOTDOT.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core//)</td>
<td><samp>[/](../cljs.core/SLASH.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/<)</td>
<td><samp>[<](../cljs.core/LT.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/<=)</td>
<td><samp>[<=](../cljs.core/LTEQ.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/=)</td>
<td><samp>[=](../cljs.core/EQ.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/==)</td>
<td><samp>[==](../cljs.core/EQEQ.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/%3E)</td>
<td><samp>[>](../cljs.core/GT.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/%3E=)</td>
<td><samp>[>=](../cljs.core/GTEQ.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/aclone)</td>
<td><samp>[aclone](../cljs.core/aclone.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[add-to-string-hash-cache](../cljs.core/add-to-string-hash-cache.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/add-watch)</td>
<td><samp>[add-watch](../cljs.core/add-watch.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/aget)</td>
<td><samp>[aget](../cljs.core/aget.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/alength)</td>
<td><samp>[alength](../cljs.core/alength.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/alter-meta!)</td>
<td><samp>[alter-meta!](../cljs.core/alter-metaBANG.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/amap)</td>
<td><samp>[amap](../cljs.core/amap.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/ancestors)</td>
<td><samp>[ancestors](../cljs.core/ancestors.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/and)</td>
<td><samp>[and](../cljs.core/and.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/apply)</td>
<td><samp>[apply](../cljs.core/apply.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/areduce)</td>
<td><samp>[areduce](../cljs.core/areduce.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[array](../cljs.core/array.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[array-chunk](../cljs.core/array-chunk.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[array-iter](../cljs.core/array-iter.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[array-list](../cljs.core/array-list.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/array-map)</td>
<td><samp>[array-map](../cljs.core/array-map.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[array-seq](../cljs.core/array-seq.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[array?](../cljs.core/arrayQMARK.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/as-%3E) <samp>→</samp></td>
<td><samp>[as->](../cljs.core/as-GT.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/aset)</td>
<td><samp>[aset](../cljs.core/aset.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/assert)</td>
<td><samp>[assert](../cljs.core/assert.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/assoc)</td>
<td><samp>[assoc](../cljs.core/assoc.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/assoc!)</td>
<td><samp>[assoc!](../cljs.core/assocBANG.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/assoc-in)</td>
<td><samp>[assoc-in](../cljs.core/assoc-in.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/associative?)</td>
<td><samp>[associative?](../cljs.core/associativeQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/atom)</td>
<td><samp>[atom](../cljs.core/atom.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/binding)</td>
<td><samp>[binding](../cljs.core/binding.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/bit-and)</td>
<td><samp>[bit-and](../cljs.core/bit-and.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/bit-and-not)</td>
<td><samp>[bit-and-not](../cljs.core/bit-and-not.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/bit-clear)</td>
<td><samp>[bit-clear](../cljs.core/bit-clear.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[bit-count](../cljs.core/bit-count.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/bit-flip)</td>
<td><samp>[bit-flip](../cljs.core/bit-flip.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/bit-not)</td>
<td><samp>[bit-not](../cljs.core/bit-not.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/bit-or)</td>
<td><samp>[bit-or](../cljs.core/bit-or.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/bit-set)</td>
<td><samp>[bit-set](../cljs.core/bit-set.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/bit-shift-left)</td>
<td><samp>[bit-shift-left](../cljs.core/bit-shift-left.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/bit-shift-right)</td>
<td><samp>[bit-shift-right](../cljs.core/bit-shift-right.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[bit-shift-right-zero-fill](../cljs.core/bit-shift-right-zero-fill.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/bit-test)</td>
<td><samp>[bit-test](../cljs.core/bit-test.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/bit-xor)</td>
<td><samp>[bit-xor](../cljs.core/bit-xor.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/boolean)</td>
<td><samp>[boolean](../cljs.core/boolean.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/booleans)</td>
<td><samp>[booleans](../cljs.core/booleans.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/butlast)</td>
<td><samp>[butlast](../cljs.core/butlast.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/byte)</td>
<td><samp>[byte](../cljs.core/byte.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/bytes)</td>
<td><samp>[bytes](../cljs.core/bytes.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/case)</td>
<td><samp>[case](../cljs.core/case.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[cat](../cljs.core/cat.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2341"><img valign="middle" alt="[+] 0.0-2341" title="Added in 0.0-2341" src="https://img.shields.io/badge/+-0.0--2341-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/char)</td>
<td><samp>[char](../cljs.core/char.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/chars)</td>
<td><samp>[chars](../cljs.core/chars.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[chunk](../cljs.core/chunk.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[chunk-append](../cljs.core/chunk-append.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[chunk-buffer](../cljs.core/chunk-buffer.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[chunk-cons](../cljs.core/chunk-cons.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[chunk-first](../cljs.core/chunk-first.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[chunk-next](../cljs.core/chunk-next.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[chunk-rest](../cljs.core/chunk-rest.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[chunked-seq](../cljs.core/chunked-seq.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[chunked-seq?](../cljs.core/chunked-seqQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[clj->js](../cljs.core/clj-GTjs.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1552"><img valign="middle" alt="[+] 0.0-1552" title="Added in 0.0-1552" src="https://img.shields.io/badge/+-0.0--1552-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[clone](../cljs.core/clone.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2134"><img valign="middle" alt="[+] 0.0-2134" title="Added in 0.0-2134" src="https://img.shields.io/badge/+-0.0--2134-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[cloneable?](../cljs.core/cloneableQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2156"><img valign="middle" alt="[+] 0.0-2156" title="Added in 0.0-2156" src="https://img.shields.io/badge/+-0.0--2156-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/coll?)</td>
<td><samp>[coll?](../cljs.core/collQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/comment) <samp>→</samp></td>
<td><samp>[comment](../cljs.core/comment.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/comp)</td>
<td><samp>[comp](../cljs.core/comp.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/comparator)</td>
<td><samp>[comparator](../cljs.core/comparator.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1586"><img valign="middle" alt="[+] 0.0-1586" title="Added in 0.0-1586" src="https://img.shields.io/badge/+-0.0--1586-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/compare)</td>
<td><samp>[compare](../cljs.core/compare.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/compare-and-set!)</td>
<td><samp>[compare-and-set!](../cljs.core/compare-and-setBANG.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/complement)</td>
<td><samp>[complement](../cljs.core/complement.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[completing](../cljs.core/completing.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2341"><img valign="middle" alt="[+] 0.0-2341" title="Added in 0.0-2341" src="https://img.shields.io/badge/+-0.0--2341-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/concat)</td>
<td><samp>[concat](../cljs.core/concat.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/cond) <samp>→</samp></td>
<td><samp>[cond](../cljs.core/cond.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/cond-%3E) <samp>→</samp></td>
<td><samp>[cond->](../cljs.core/cond-GT.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/cond-%3E%3E) <samp>→</samp></td>
<td><samp>[cond->>](../cljs.core/cond-GTGT.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/condp)</td>
<td><samp>[condp](../cljs.core/condp.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/conj)</td>
<td><samp>[conj](../cljs.core/conj.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/conj!)</td>
<td><samp>[conj!](../cljs.core/conjBANG.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/cons)</td>
<td><samp>[cons](../cljs.core/cons.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/constantly)</td>
<td><samp>[constantly](../cljs.core/constantly.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/contains?)</td>
<td><samp>[contains?](../cljs.core/containsQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/count)</td>
<td><samp>[count](../cljs.core/count.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/counted?)</td>
<td><samp>[counted?](../cljs.core/countedQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/cycle)</td>
<td><samp>[cycle](../cljs.core/cycle.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/dec)</td>
<td><samp>[dec](../cljs.core/dec.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/declare) <samp>→</samp></td>
<td><samp>[declare](../cljs.core/declare.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[dedupe](../cljs.core/dedupe.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/defmacro) <samp>→</samp></td>
<td><samp>[defmacro](../cljs.core/defmacro.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/defmethod)</td>
<td><samp>[defmethod](../cljs.core/defmethod.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/defmulti)</td>
<td><samp>[defmulti](../cljs.core/defmulti.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/defn) <samp>→</samp></td>
<td><samp>[defn](../cljs.core/defn.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/defn-) <samp>→</samp></td>
<td><samp>[defn-](../cljs.core/defn-.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/defonce)</td>
<td><samp>[defonce](../cljs.core/defonce.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2156"><img valign="middle" alt="[+] 0.0-2156" title="Added in 0.0-2156" src="https://img.shields.io/badge/+-0.0--2156-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/defprotocol)</td>
<td><samp>[defprotocol](../cljs.core/defprotocol.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/defrecord)</td>
<td><samp>[defrecord](../cljs.core/defrecord.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/deftype)</td>
<td><samp>[deftype](../cljs.core/deftype.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/delay)</td>
<td><samp>[delay](../cljs.core/delay.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/delay?)</td>
<td><samp>[delay?](../cljs.core/delayQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/deref)</td>
<td><samp>[deref](../cljs.core/deref.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/derive)</td>
<td><samp>[derive](../cljs.core/derive.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/descendants)</td>
<td><samp>[descendants](../cljs.core/descendants.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/disj)</td>
<td><samp>[disj](../cljs.core/disj.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/disj!)</td>
<td><samp>[disj!](../cljs.core/disjBANG.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/dissoc)</td>
<td><samp>[dissoc](../cljs.core/dissoc.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/dissoc!)</td>
<td><samp>[dissoc!](../cljs.core/dissocBANG.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/distinct)</td>
<td><samp>[distinct](../cljs.core/distinct.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/distinct?)</td>
<td><samp>[distinct?](../cljs.core/distinctQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[divide](../cljs.core/divide.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/doall)</td>
<td><samp>[doall](../cljs.core/doall.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/dorun)</td>
<td><samp>[dorun](../cljs.core/dorun.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/doseq)</td>
<td><samp>[doseq](../cljs.core/doseq.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/dotimes)</td>
<td><samp>[dotimes](../cljs.core/dotimes.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/doto) <samp>→</samp></td>
<td><samp>[doto](../cljs.core/doto.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/double)</td>
<td><samp>[double](../cljs.core/double.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/double-array)</td>
<td><samp>[double-array](../cljs.core/double-array.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/doubles)</td>
<td><samp>[doubles](../cljs.core/doubles.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/drop)</td>
<td><samp>[drop](../cljs.core/drop.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/drop-last)</td>
<td><samp>[drop-last](../cljs.core/drop-last.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/drop-while)</td>
<td><samp>[drop-while](../cljs.core/drop-while.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[eduction](../cljs.core/eduction.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2371"><img valign="middle" alt="[+] 0.0-2371" title="Added in 0.0-2371" src="https://img.shields.io/badge/+-0.0--2371-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/empty)</td>
<td><samp>[empty](../cljs.core/empty.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/empty?)</td>
<td><samp>[empty?](../cljs.core/emptyQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[enable-console-print!](../cljs.core/enable-console-printBANG.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2060"><img valign="middle" alt="[+] 0.0-2060" title="Added in 0.0-2060" src="https://img.shields.io/badge/+-0.0--2060-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[ensure-reduced](../cljs.core/ensure-reduced.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2411"><img valign="middle" alt="[+] 0.0-2411" title="Added in 0.0-2411" src="https://img.shields.io/badge/+-0.0--2411-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[es6-entries-iterator](../cljs.core/es6-entries-iterator.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2371"><img valign="middle" alt="[+] 0.0-2371" title="Added in 0.0-2371" src="https://img.shields.io/badge/+-0.0--2371-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[es6-iterable](../cljs.core/es6-iterable.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2411"><img valign="middle" alt="[+] 0.0-2411" title="Added in 0.0-2411" src="https://img.shields.io/badge/+-0.0--2411-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[es6-iterator](../cljs.core/es6-iterator.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2371"><img valign="middle" alt="[+] 0.0-2371" title="Added in 0.0-2371" src="https://img.shields.io/badge/+-0.0--2371-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[es6-iterator-seq](../cljs.core/es6-iterator-seq.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2411"><img valign="middle" alt="[+] 0.0-2411" title="Added in 0.0-2411" src="https://img.shields.io/badge/+-0.0--2411-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[es6-set-entries-iterator](../cljs.core/es6-set-entries-iterator.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2371"><img valign="middle" alt="[+] 0.0-2371" title="Added in 0.0-2371" src="https://img.shields.io/badge/+-0.0--2371-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/even?)</td>
<td><samp>[even?](../cljs.core/evenQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/every-pred)</td>
<td><samp>[every-pred](../cljs.core/every-pred.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/every?)</td>
<td><samp>[every?](../cljs.core/everyQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[ex-cause](../cljs.core/ex-cause.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1576"><img valign="middle" alt="[+] 0.0-1576" title="Added in 0.0-1576" src="https://img.shields.io/badge/+-0.0--1576-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/ex-data)</td>
<td><samp>[ex-data](../cljs.core/ex-data.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1576"><img valign="middle" alt="[+] 0.0-1576" title="Added in 0.0-1576" src="https://img.shields.io/badge/+-0.0--1576-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/ex-info)</td>
<td><samp>[ex-info](../cljs.core/ex-info.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1576"><img valign="middle" alt="[+] 0.0-1576" title="Added in 0.0-1576" src="https://img.shields.io/badge/+-0.0--1576-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[ex-message](../cljs.core/ex-message.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1576"><img valign="middle" alt="[+] 0.0-1576" title="Added in 0.0-1576" src="https://img.shields.io/badge/+-0.0--1576-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[exists?](../cljs.core/existsQMARK.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/extend-protocol) <samp>→</samp></td>
<td><samp>[extend-protocol](../cljs.core/extend-protocol.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/extend-type)</td>
<td><samp>[extend-type](../cljs.core/extend-type.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/false?)</td>
<td><samp>[false?](../cljs.core/falseQMARK.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/ffirst)</td>
<td><samp>[ffirst](../cljs.core/ffirst.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/filter)</td>
<td><samp>[filter](../cljs.core/filter.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/filterv)</td>
<td><samp>[filterv](../cljs.core/filterv.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/find)</td>
<td><samp>[find](../cljs.core/find.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/first)</td>
<td><samp>[first](../cljs.core/first.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/flatten)</td>
<td><samp>[flatten](../cljs.core/flatten.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/float)</td>
<td><samp>[float](../cljs.core/float.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/floats)</td>
<td><samp>[floats](../cljs.core/floats.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/flush)</td>
<td><samp>[flush](../cljs.core/flush.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/fn) <samp>→</samp></td>
<td><samp>[fn](../cljs.core/fn.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/fn?)</td>
<td><samp>[fn?](../cljs.core/fnQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/fnext)</td>
<td><samp>[fnext](../cljs.core/fnext.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/fnil)</td>
<td><samp>[fnil](../cljs.core/fnil.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/for)</td>
<td><samp>[for](../cljs.core/for.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/force)</td>
<td><samp>[force](../cljs.core/force.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/frequencies)</td>
<td><samp>[frequencies](../cljs.core/frequencies.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[gen-apply-to](../cljs.core/gen-apply-to.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/gensym)</td>
<td><samp>[gensym](../cljs.core/gensym.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/get)</td>
<td><samp>[get](../cljs.core/get.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/get-in)</td>
<td><samp>[get-in](../cljs.core/get-in.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/get-method)</td>
<td><samp>[get-method](../cljs.core/get-method.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/get-validator)</td>
<td><samp>[get-validator](../cljs.core/get-validator.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/group-by)</td>
<td><samp>[group-by](../cljs.core/group-by.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/hash)</td>
<td><samp>[hash](../cljs.core/hash.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[hash-combine](../cljs.core/hash-combine.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[hash-keyword](../cljs.core/hash-keyword.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2261"><img valign="middle" alt="[+] 0.0-2261" title="Added in 0.0-2261" src="https://img.shields.io/badge/+-0.0--2261-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/hash-map)</td>
<td><samp>[hash-map](../cljs.core/hash-map.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/hash-ordered-coll)</td>
<td><samp>[hash-ordered-coll](../cljs.core/hash-ordered-coll.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2261"><img valign="middle" alt="[+] 0.0-2261" title="Added in 0.0-2261" src="https://img.shields.io/badge/+-0.0--2261-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/hash-set)</td>
<td><samp>[hash-set](../cljs.core/hash-set.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1443"><img valign="middle" alt="[+] 0.0-1443" title="Added in 0.0-1443" src="https://img.shields.io/badge/+-0.0--1443-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[hash-string](../cljs.core/hash-string.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2261"><img valign="middle" alt="[+] 0.0-2261" title="Added in 0.0-2261" src="https://img.shields.io/badge/+-0.0--2261-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[hash-string\*](../cljs.core/hash-stringSTAR.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2261"><img valign="middle" alt="[+] 0.0-2261" title="Added in 0.0-2261" src="https://img.shields.io/badge/+-0.0--2261-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/hash-unordered-coll)</td>
<td><samp>[hash-unordered-coll](../cljs.core/hash-unordered-coll.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2261"><img valign="middle" alt="[+] 0.0-2261" title="Added in 0.0-2261" src="https://img.shields.io/badge/+-0.0--2261-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/identical?)</td>
<td><samp>[identical?](../cljs.core/identicalQMARK.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/identity)</td>
<td><samp>[identity](../cljs.core/identity.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/if-let) <samp>→</samp></td>
<td><samp>[if-let](../cljs.core/if-let.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/if-not) <samp>→</samp></td>
<td><samp>[if-not](../cljs.core/if-not.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/if-some) <samp>→</samp></td>
<td><samp>[if-some](../cljs.core/if-some.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2261"><img valign="middle" alt="[+] 0.0-2261" title="Added in 0.0-2261" src="https://img.shields.io/badge/+-0.0--2261-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/ifn?)</td>
<td><samp>[ifn?](../cljs.core/ifnQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[implements?](../cljs.core/implementsQMARK.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2014"><img valign="middle" alt="[+] 0.0-2014" title="Added in 0.0-2014" src="https://img.shields.io/badge/+-0.0--2014-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[import-macros](../cljs.core/import-macros.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/inc)</td>
<td><samp>[inc](../cljs.core/inc.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[indexed?](../cljs.core/indexedQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/instance?)</td>
<td><samp>[instance?](../cljs.core/instanceQMARK.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/int)</td>
<td><samp>[int](../cljs.core/int.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/int-array)</td>
<td><samp>[int-array](../cljs.core/int-array.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[int-rotate-left](../cljs.core/int-rotate-left.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2261"><img valign="middle" alt="[+] 0.0-2261" title="Added in 0.0-2261" src="https://img.shields.io/badge/+-0.0--2261-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/integer?)</td>
<td><samp>[integer?](../cljs.core/integerQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/interleave)</td>
<td><samp>[interleave](../cljs.core/interleave.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/interpose)</td>
<td><samp>[interpose](../cljs.core/interpose.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/into)</td>
<td><samp>[into](../cljs.core/into.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/into-array)</td>
<td><samp>[into-array](../cljs.core/into-array.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/ints)</td>
<td><samp>[ints](../cljs.core/ints.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[is_proto_](../cljs.core/is_proto_.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/isa?)</td>
<td><samp>[isa?](../cljs.core/isaQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[iter](../cljs.core/iter.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[iterable?](../cljs.core/iterableQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2356"><img valign="middle" alt="[+] 0.0-2356" title="Added in 0.0-2356" src="https://img.shields.io/badge/+-0.0--2356-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/iterate)</td>
<td><samp>[iterate](../cljs.core/iterate.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[js->clj](../cljs.core/js-GTclj.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[js-debugger](../cljs.core/js-debugger.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2496"><img valign="middle" alt="[+] 0.0-2496" title="Added in 0.0-2496" src="https://img.shields.io/badge/+-0.0--2496-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[js-delete](../cljs.core/js-delete.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[js-in](../cljs.core/js-in.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2411"><img valign="middle" alt="[+] 0.0-2411" title="Added in 0.0-2411" src="https://img.shields.io/badge/+-0.0--2411-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[js-invoke](../cljs.core/js-invoke.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2411"><img valign="middle" alt="[+] 0.0-2411" title="Added in 0.0-2411" src="https://img.shields.io/badge/+-0.0--2411-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[js-keys](../cljs.core/js-keys.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[js-mod](../cljs.core/js-mod.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1552"><img valign="middle" alt="[+] 0.0-1552" title="Added in 0.0-1552" src="https://img.shields.io/badge/+-0.0--1552-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[js-obj](../cljs.core/js-obj.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[js-str](../cljs.core/js-str.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2341"><img valign="middle" alt="[+] 0.0-2341" title="Added in 0.0-2341" src="https://img.shields.io/badge/+-0.0--2341-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/juxt)</td>
<td><samp>[juxt](../cljs.core/juxt.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/keep)</td>
<td><samp>[keep](../cljs.core/keep.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/keep-indexed)</td>
<td><samp>[keep-indexed](../cljs.core/keep-indexed.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/key)</td>
<td><samp>[key](../cljs.core/key.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[key->js](../cljs.core/key-GTjs.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[key-test](../cljs.core/key-test.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/keys)</td>
<td><samp>[keys](../cljs.core/keys.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/keyword)</td>
<td><samp>[keyword](../cljs.core/keyword.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[keyword-identical?](../cljs.core/keyword-identicalQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1877"><img valign="middle" alt="[+] 0.0-1877" title="Added in 0.0-1877" src="https://img.shields.io/badge/+-0.0--1877-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/keyword?)</td>
<td><samp>[keyword?](../cljs.core/keywordQMARK.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/last)</td>
<td><samp>[last](../cljs.core/last.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/lazy-cat)</td>
<td><samp>[lazy-cat](../cljs.core/lazy-cat.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1803"><img valign="middle" alt="[+] 0.0-1803" title="Added in 0.0-1803" src="https://img.shields.io/badge/+-0.0--1803-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/lazy-seq)</td>
<td><samp>[lazy-seq](../cljs.core/lazy-seq.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[lazy-transformer](../cljs.core/lazy-transformer.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/let)</td>
<td><samp>[let](../cljs.core/let.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/letfn) <samp>→</samp></td>
<td><samp>[letfn](../cljs.core/letfn.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/list)</td>
<td><samp>[list](../cljs.core/list.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/list*)</td>
<td><samp>[list\*](../cljs.core/listSTAR.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/list?)</td>
<td><samp>[list?](../cljs.core/listQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[load-file\*](../cljs.core/load-fileSTAR.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2719"><img valign="middle" alt="[+] 0.0-2719" title="Added in 0.0-2719" src="https://img.shields.io/badge/+-0.0--2719-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/long)</td>
<td><samp>[long](../cljs.core/long.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/long-array)</td>
<td><samp>[long-array](../cljs.core/long-array.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/longs)</td>
<td><samp>[longs](../cljs.core/longs.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/loop)</td>
<td><samp>[loop](../cljs.core/loop.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[m3-C1](../cljs.core/m3-C1.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2261"><img valign="middle" alt="[+] 0.0-2261" title="Added in 0.0-2261" src="https://img.shields.io/badge/+-0.0--2261-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[m3-C2](../cljs.core/m3-C2.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2261"><img valign="middle" alt="[+] 0.0-2261" title="Added in 0.0-2261" src="https://img.shields.io/badge/+-0.0--2261-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[m3-fmix](../cljs.core/m3-fmix.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2261"><img valign="middle" alt="[+] 0.0-2261" title="Added in 0.0-2261" src="https://img.shields.io/badge/+-0.0--2261-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[m3-hash-int](../cljs.core/m3-hash-int.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2261"><img valign="middle" alt="[+] 0.0-2261" title="Added in 0.0-2261" src="https://img.shields.io/badge/+-0.0--2261-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[m3-hash-unencoded-chars](../cljs.core/m3-hash-unencoded-chars.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2261"><img valign="middle" alt="[+] 0.0-2261" title="Added in 0.0-2261" src="https://img.shields.io/badge/+-0.0--2261-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[m3-mix-H1](../cljs.core/m3-mix-H1.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2261"><img valign="middle" alt="[+] 0.0-2261" title="Added in 0.0-2261" src="https://img.shields.io/badge/+-0.0--2261-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[m3-mix-K1](../cljs.core/m3-mix-K1.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2261"><img valign="middle" alt="[+] 0.0-2261" title="Added in 0.0-2261" src="https://img.shields.io/badge/+-0.0--2261-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[m3-seed](../cljs.core/m3-seed.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2261"><img valign="middle" alt="[+] 0.0-2261" title="Added in 0.0-2261" src="https://img.shields.io/badge/+-0.0--2261-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/make-array)</td>
<td><samp>[make-array](../cljs.core/make-array.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/make-hierarchy)</td>
<td><samp>[make-hierarchy](../cljs.core/make-hierarchy.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/map)</td>
<td><samp>[map](../cljs.core/map.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/map-indexed)</td>
<td><samp>[map-indexed](../cljs.core/map-indexed.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/map?)</td>
<td><samp>[map?](../cljs.core/mapQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/mapcat)</td>
<td><samp>[mapcat](../cljs.core/mapcat.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/mapv)</td>
<td><samp>[mapv](../cljs.core/mapv.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/max)</td>
<td><samp>[max](../cljs.core/max.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/max-key)</td>
<td><samp>[max-key](../cljs.core/max-key.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/memfn) <samp>→</samp></td>
<td><samp>[memfn](../cljs.core/memfn.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1443"><img valign="middle" alt="[+] 0.0-1443" title="Added in 0.0-1443" src="https://img.shields.io/badge/+-0.0--1443-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/memoize)</td>
<td><samp>[memoize](../cljs.core/memoize.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/merge)</td>
<td><samp>[merge](../cljs.core/merge.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/merge-with)</td>
<td><samp>[merge-with](../cljs.core/merge-with.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/meta)</td>
<td><samp>[meta](../cljs.core/meta.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/methods)</td>
<td><samp>[methods](../cljs.core/methods.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/min)</td>
<td><samp>[min](../cljs.core/min.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/min-key)</td>
<td><samp>[min-key](../cljs.core/min-key.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[missing-protocol](../cljs.core/missing-protocol.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/mix-collection-hash)</td>
<td><samp>[mix-collection-hash](../cljs.core/mix-collection-hash.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2261"><img valign="middle" alt="[+] 0.0-2261" title="Added in 0.0-2261" src="https://img.shields.io/badge/+-0.0--2261-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[mk-bound-fn](../cljs.core/mk-bound-fn.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/mod)</td>
<td><samp>[mod](../cljs.core/mod.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[multi-stepper](../cljs.core/multi-stepper.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/name)</td>
<td><samp>[name](../cljs.core/name.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/namespace)</td>
<td><samp>[namespace](../cljs.core/namespace.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/neg?)</td>
<td><samp>[neg?](../cljs.core/negQMARK.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/newline)</td>
<td><samp>[newline](../cljs.core/newline.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/next)</td>
<td><samp>[next](../cljs.core/next.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/nfirst)</td>
<td><samp>[nfirst](../cljs.core/nfirst.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[nil-iter](../cljs.core/nil-iter.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/nil?)</td>
<td><samp>[nil?](../cljs.core/nilQMARK.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/nnext)</td>
<td><samp>[nnext](../cljs.core/nnext.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/not)</td>
<td><samp>[not](../cljs.core/not.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/not-any?)</td>
<td><samp>[not-any?](../cljs.core/not-anyQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/not-empty)</td>
<td><samp>[not-empty](../cljs.core/not-empty.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/not-every?)</td>
<td><samp>[not-every?](../cljs.core/not-everyQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[not-native](../cljs.core/not-native.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/not=)</td>
<td><samp>[not=](../cljs.core/notEQ.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/ns-interns)</td>
<td><samp>[ns-interns](../cljs.core/ns-interns.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2496"><img valign="middle" alt="[+] 0.0-2496" title="Added in 0.0-2496" src="https://img.shields.io/badge/+-0.0--2496-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/nth)</td>
<td><samp>[nth](../cljs.core/nth.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/nthnext)</td>
<td><samp>[nthnext](../cljs.core/nthnext.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/nthrest)</td>
<td><samp>[nthrest](../cljs.core/nthrest.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2411"><img valign="middle" alt="[+] 0.0-2411" title="Added in 0.0-2411" src="https://img.shields.io/badge/+-0.0--2411-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/number?)</td>
<td><samp>[number?](../cljs.core/numberQMARK.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[obj-map](../cljs.core/obj-map.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1443"><img valign="middle" alt="[+] 0.0-1443" title="Added in 0.0-1443" src="https://img.shields.io/badge/+-0.0--1443-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/object-array)</td>
<td><samp>[object-array](../cljs.core/object-array.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[object?](../cljs.core/objectQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2120"><img valign="middle" alt="[+] 0.0-2120" title="Added in 0.0-2120" src="https://img.shields.io/badge/+-0.0--2120-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/odd?)</td>
<td><samp>[odd?](../cljs.core/oddQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/or)</td>
<td><samp>[or](../cljs.core/or.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/parents)</td>
<td><samp>[parents](../cljs.core/parents.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/partial)</td>
<td><samp>[partial](../cljs.core/partial.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/partition)</td>
<td><samp>[partition](../cljs.core/partition.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/partition-all)</td>
<td><samp>[partition-all](../cljs.core/partition-all.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/partition-by)</td>
<td><samp>[partition-by](../cljs.core/partition-by.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/peek)</td>
<td><samp>[peek](../cljs.core/peek.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/persistent!)</td>
<td><samp>[persistent!](../cljs.core/persistentBANG.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[persistent-array-map-seq](../cljs.core/persistent-array-map-seq.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1820"><img valign="middle" alt="[+] 0.0-1820" title="Added in 0.0-1820" src="https://img.shields.io/badge/+-0.0--1820-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/pop)</td>
<td><samp>[pop](../cljs.core/pop.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/pop!)</td>
<td><samp>[pop!](../cljs.core/popBANG.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/pos?)</td>
<td><samp>[pos?](../cljs.core/posQMARK.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/pr)</td>
<td><samp>[pr](../cljs.core/pr.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[pr-seq-writer](../cljs.core/pr-seq-writer.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1503"><img valign="middle" alt="[+] 0.0-1503" title="Added in 0.0-1503" src="https://img.shields.io/badge/+-0.0--1503-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[pr-sequential-writer](../cljs.core/pr-sequential-writer.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1503"><img valign="middle" alt="[+] 0.0-1503" title="Added in 0.0-1503" src="https://img.shields.io/badge/+-0.0--1503-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/pr-str)</td>
<td><samp>[pr-str](../cljs.core/pr-str.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[pr-str\*](../cljs.core/pr-strSTAR.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1806"><img valign="middle" alt="[+] 0.0-1806" title="Added in 0.0-1806" src="https://img.shields.io/badge/+-0.0--1806-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[pr-str-with-opts](../cljs.core/pr-str-with-opts.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/prefer-method)</td>
<td><samp>[prefer-method](../cljs.core/prefer-method.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/prefers)</td>
<td><samp>[prefers](../cljs.core/prefers.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[prim-seq](../cljs.core/prim-seq.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/print)</td>
<td><samp>[print](../cljs.core/print.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[print-map](../cljs.core/print-map.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2120"><img valign="middle" alt="[+] 0.0-2120" title="Added in 0.0-2120" src="https://img.shields.io/badge/+-0.0--2120-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/print-str)</td>
<td><samp>[print-str](../cljs.core/print-str.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1011"><img valign="middle" alt="[+] 0.0-1011" title="Added in 0.0-1011" src="https://img.shields.io/badge/+-0.0--1011-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/println)</td>
<td><samp>[println](../cljs.core/println.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/println-str)</td>
<td><samp>[println-str](../cljs.core/println-str.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1011"><img valign="middle" alt="[+] 0.0-1011" title="Added in 0.0-1011" src="https://img.shields.io/badge/+-0.0--1011-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/prn)</td>
<td><samp>[prn](../cljs.core/prn.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/prn-str)</td>
<td><samp>[prn-str](../cljs.core/prn-str.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1011"><img valign="middle" alt="[+] 0.0-1011" title="Added in 0.0-1011" src="https://img.shields.io/badge/+-0.0--1011-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[prn-str-with-opts](../cljs.core/prn-str-with-opts.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1011"><img valign="middle" alt="[+] 0.0-1011" title="Added in 0.0-1011" src="https://img.shields.io/badge/+-0.0--1011-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/quot)</td>
<td><samp>[quot](../cljs.core/quot.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/rand)</td>
<td><samp>[rand](../cljs.core/rand.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/rand-int)</td>
<td><samp>[rand-int](../cljs.core/rand-int.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/rand-nth)</td>
<td><samp>[rand-nth](../cljs.core/rand-nth.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[random-sample](../cljs.core/random-sample.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/range)</td>
<td><samp>[range](../cljs.core/range.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[ranged-iterator](../cljs.core/ranged-iterator.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2371"><img valign="middle" alt="[+] 0.0-2371" title="Added in 0.0-2371" src="https://img.shields.io/badge/+-0.0--2371-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/re-find)</td>
<td><samp>[re-find](../cljs.core/re-find.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/re-matches)</td>
<td><samp>[re-matches](../cljs.core/re-matches.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/re-pattern)</td>
<td><samp>[re-pattern](../cljs.core/re-pattern.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/re-seq)</td>
<td><samp>[re-seq](../cljs.core/re-seq.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/realized?)</td>
<td><samp>[realized?](../cljs.core/realizedQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/reduce)</td>
<td><samp>[reduce](../cljs.core/reduce.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/reduce-kv)</td>
<td><samp>[reduce-kv](../cljs.core/reduce-kv.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[reduceable?](../cljs.core/reduceableQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/reduced)</td>
<td><samp>[reduced](../cljs.core/reduced.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/reduced?)</td>
<td><samp>[reduced?](../cljs.core/reducedQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/reductions)</td>
<td><samp>[reductions](../cljs.core/reductions.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[regexp?](../cljs.core/regexpQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/reify)</td>
<td><samp>[reify](../cljs.core/reify.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/rem)</td>
<td><samp>[rem](../cljs.core/rem.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/remove)</td>
<td><samp>[remove](../cljs.core/remove.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/remove-all-methods)</td>
<td><samp>[remove-all-methods](../cljs.core/remove-all-methods.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/remove-method)</td>
<td><samp>[remove-method](../cljs.core/remove-method.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/remove-watch)</td>
<td><samp>[remove-watch](../cljs.core/remove-watch.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/repeat)</td>
<td><samp>[repeat](../cljs.core/repeat.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/repeatedly)</td>
<td><samp>[repeatedly](../cljs.core/repeatedly.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/replace)</td>
<td><samp>[replace](../cljs.core/replace.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/replicate)</td>
<td><samp>[replicate](../cljs.core/replicate.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/reset!)</td>
<td><samp>[reset!](../cljs.core/resetBANG.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/reset-meta!)</td>
<td><samp>[reset-meta!](../cljs.core/reset-metaBANG.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/rest)</td>
<td><samp>[rest](../cljs.core/rest.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/reverse)</td>
<td><samp>[reverse](../cljs.core/reverse.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/reversible?)</td>
<td><samp>[reversible?](../cljs.core/reversibleQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/rseq)</td>
<td><samp>[rseq](../cljs.core/rseq.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/rsubseq)</td>
<td><samp>[rsubseq](../cljs.core/rsubseq.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[run!](../cljs.core/runBANG.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/satisfies?)</td>
<td><samp>[satisfies?](../cljs.core/satisfiesQMARK.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/second)</td>
<td><samp>[second](../cljs.core/second.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/select-keys)</td>
<td><samp>[select-keys](../cljs.core/select-keys.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/seq)</td>
<td><samp>[seq](../cljs.core/seq.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[seq-iter](../cljs.core/seq-iter.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/seq?)</td>
<td><samp>[seq?](../cljs.core/seqQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[seqable?](../cljs.core/seqableQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/sequence)</td>
<td><samp>[sequence](../cljs.core/sequence.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2120"><img valign="middle" alt="[+] 0.0-2120" title="Added in 0.0-2120" src="https://img.shields.io/badge/+-0.0--2120-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/sequential?)</td>
<td><samp>[sequential?](../cljs.core/sequentialQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/set)</td>
<td><samp>[set](../cljs.core/set.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[set-from-indexed-seq](../cljs.core/set-from-indexed-seq.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1877"><img valign="middle" alt="[+] 0.0-1877" title="Added in 0.0-1877" src="https://img.shields.io/badge/+-0.0--1877-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[set-print-fn!](../cljs.core/set-print-fnBANG.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/set-validator!)</td>
<td><samp>[set-validator!](../cljs.core/set-validatorBANG.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/set?)</td>
<td><samp>[set?](../cljs.core/setQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/short)</td>
<td><samp>[short](../cljs.core/short.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/shorts)</td>
<td><samp>[shorts](../cljs.core/shorts.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/shuffle)</td>
<td><samp>[shuffle](../cljs.core/shuffle.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[simple-benchmark](../cljs.core/simple-benchmark.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1236"><img valign="middle" alt="[+] 0.0-1236" title="Added in 0.0-1236" src="https://img.shields.io/badge/+-0.0--1236-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/some)</td>
<td><samp>[some](../cljs.core/some.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/some-%3E) <samp>→</samp></td>
<td><samp>[some->](../cljs.core/some-GT.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/some-%3E%3E) <samp>→</samp></td>
<td><samp>[some->>](../cljs.core/some-GTGT.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/some-fn)</td>
<td><samp>[some-fn](../cljs.core/some-fn.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/some?)</td>
<td><samp>[some?](../cljs.core/someQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2261"><img valign="middle" alt="[+] 0.0-2261" title="Added in 0.0-2261" src="https://img.shields.io/badge/+-0.0--2261-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/sort)</td>
<td><samp>[sort](../cljs.core/sort.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/sort-by)</td>
<td><samp>[sort-by](../cljs.core/sort-by.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/sorted-map)</td>
<td><samp>[sorted-map](../cljs.core/sorted-map.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/sorted-map-by)</td>
<td><samp>[sorted-map-by](../cljs.core/sorted-map-by.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/sorted-set)</td>
<td><samp>[sorted-set](../cljs.core/sorted-set.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/sorted-set-by)</td>
<td><samp>[sorted-set-by](../cljs.core/sorted-set-by.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/sorted?)</td>
<td><samp>[sorted?](../cljs.core/sortedQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2120"><img valign="middle" alt="[+] 0.0-2120" title="Added in 0.0-2120" src="https://img.shields.io/badge/+-0.0--2120-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/special-symbol?)</td>
<td><samp>[special-symbol?](../cljs.core/special-symbolQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1803"><img valign="middle" alt="[+] 0.0-1803" title="Added in 0.0-1803" src="https://img.shields.io/badge/+-0.0--1803-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[specify](../cljs.core/specify.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2138"><img valign="middle" alt="[+] 0.0-2138" title="Added in 0.0-2138" src="https://img.shields.io/badge/+-0.0--2138-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[specify!](../cljs.core/specifyBANG.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2156"><img valign="middle" alt="[+] 0.0-2156" title="Added in 0.0-2156" src="https://img.shields.io/badge/+-0.0--2156-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/split-at)</td>
<td><samp>[split-at](../cljs.core/split-at.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/split-with)</td>
<td><samp>[split-with](../cljs.core/split-with.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[spread](../cljs.core/spread.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[stepper](../cljs.core/stepper.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/str)</td>
<td><samp>[str](../cljs.core/str.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[string-hash-cache](../cljs.core/string-hash-cache.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[string-hash-cache-count](../cljs.core/string-hash-cache-count.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[string-iter](../cljs.core/string-iter.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[string-print](../cljs.core/string-print.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/string?)</td>
<td><samp>[string?](../cljs.core/stringQMARK.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/subs)</td>
<td><samp>[subs](../cljs.core/subs.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/subseq)</td>
<td><samp>[subseq](../cljs.core/subseq.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/subvec)</td>
<td><samp>[subvec](../cljs.core/subvec.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/swap!)</td>
<td><samp>[swap!](../cljs.core/swapBANG.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/symbol)</td>
<td><samp>[symbol](../cljs.core/symbol.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/symbol?)</td>
<td><samp>[symbol?](../cljs.core/symbolQMARK.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/take)</td>
<td><samp>[take](../cljs.core/take.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/take-last)</td>
<td><samp>[take-last](../cljs.core/take-last.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/take-nth)</td>
<td><samp>[take-nth](../cljs.core/take-nth.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/take-while)</td>
<td><samp>[take-while](../cljs.core/take-while.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/test)</td>
<td><samp>[test](../cljs.core/test.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2496"><img valign="middle" alt="[+] 0.0-2496" title="Added in 0.0-2496" src="https://img.shields.io/badge/+-0.0--2496-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[this-as](../cljs.core/this-as.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/time)</td>
<td><samp>[time](../cljs.core/time.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/to-array)</td>
<td><samp>[to-array](../cljs.core/to-array.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/to-array-2d)</td>
<td><samp>[to-array-2d](../cljs.core/to-array-2d.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/trampoline)</td>
<td><samp>[trampoline](../cljs.core/trampoline.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[transduce](../cljs.core/transduce.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/transient)</td>
<td><samp>[transient](../cljs.core/transient.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/tree-seq)</td>
<td><samp>[tree-seq](../cljs.core/tree-seq.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/true?)</td>
<td><samp>[true?](../cljs.core/trueQMARK.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/type)</td>
<td><samp>[type](../cljs.core/type.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-971"><img valign="middle" alt="[+] 0.0-971" title="Added in 0.0-971" src="https://img.shields.io/badge/+-0.0--971-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[type->str](../cljs.core/type-GTstr.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1859"><img valign="middle" alt="[+] 0.0-1859" title="Added in 0.0-1859" src="https://img.shields.io/badge/+-0.0--1859-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/unchecked-add)</td>
<td><samp>[unchecked-add](../cljs.core/unchecked-add.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/unchecked-add-int)</td>
<td><samp>[unchecked-add-int](../cljs.core/unchecked-add-int.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/unchecked-byte)</td>
<td><samp>[unchecked-byte](../cljs.core/unchecked-byte.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/unchecked-char)</td>
<td><samp>[unchecked-char](../cljs.core/unchecked-char.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/unchecked-dec)</td>
<td><samp>[unchecked-dec](../cljs.core/unchecked-dec.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/unchecked-dec-int)</td>
<td><samp>[unchecked-dec-int](../cljs.core/unchecked-dec-int.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/unchecked-divide-int)</td>
<td><samp>[unchecked-divide-int](../cljs.core/unchecked-divide-int.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/unchecked-double)</td>
<td><samp>[unchecked-double](../cljs.core/unchecked-double.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/unchecked-float)</td>
<td><samp>[unchecked-float](../cljs.core/unchecked-float.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/unchecked-inc)</td>
<td><samp>[unchecked-inc](../cljs.core/unchecked-inc.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/unchecked-inc-int)</td>
<td><samp>[unchecked-inc-int](../cljs.core/unchecked-inc-int.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/unchecked-int)</td>
<td><samp>[unchecked-int](../cljs.core/unchecked-int.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/unchecked-long)</td>
<td><samp>[unchecked-long](../cljs.core/unchecked-long.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/unchecked-multiply)</td>
<td><samp>[unchecked-multiply](../cljs.core/unchecked-multiply.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/unchecked-multiply-int)</td>
<td><samp>[unchecked-multiply-int](../cljs.core/unchecked-multiply-int.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/unchecked-negate)</td>
<td><samp>[unchecked-negate](../cljs.core/unchecked-negate.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/unchecked-negate-int)</td>
<td><samp>[unchecked-negate-int](../cljs.core/unchecked-negate-int.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/unchecked-remainder-int)</td>
<td><samp>[unchecked-remainder-int](../cljs.core/unchecked-remainder-int.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/unchecked-short)</td>
<td><samp>[unchecked-short](../cljs.core/unchecked-short.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/unchecked-subtract)</td>
<td><samp>[unchecked-subtract](../cljs.core/unchecked-subtract.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/unchecked-subtract-int)</td>
<td><samp>[unchecked-subtract-int](../cljs.core/unchecked-subtract-int.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[undefined?](../cljs.core/undefinedQMARK.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/underive)</td>
<td><samp>[underive](../cljs.core/underive.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[unreduced](../cljs.core/unreduced.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2411"><img valign="middle" alt="[+] 0.0-2411" title="Added in 0.0-2411" src="https://img.shields.io/badge/+-0.0--2411-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/unsigned-bit-shift-right)</td>
<td><samp>[unsigned-bit-shift-right](../cljs.core/unsigned-bit-shift-right.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2080"><img valign="middle" alt="[+] 0.0-2080" title="Added in 0.0-2080" src="https://img.shields.io/badge/+-0.0--2080-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[update](../cljs.core/update.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2411"><img valign="middle" alt="[+] 0.0-2411" title="Added in 0.0-2411" src="https://img.shields.io/badge/+-0.0--2411-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/update-in)</td>
<td><samp>[update-in](../cljs.core/update-in.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/val)</td>
<td><samp>[val](../cljs.core/val.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/vals)</td>
<td><samp>[vals](../cljs.core/vals.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/vary-meta)</td>
<td><samp>[vary-meta](../cljs.core/vary-meta.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/vec)</td>
<td><samp>[vec](../cljs.core/vec.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/vector)</td>
<td><samp>[vector](../cljs.core/vector.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/vector?)</td>
<td><samp>[vector?](../cljs.core/vectorQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[volatile!](../cljs.core/volatileBANG.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2496"><img valign="middle" alt="[+] 0.0-2496" title="Added in 0.0-2496" src="https://img.shields.io/badge/+-0.0--2496-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[volatile?](../cljs.core/volatileQMARK.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2496"><img valign="middle" alt="[+] 0.0-2496" title="Added in 0.0-2496" src="https://img.shields.io/badge/+-0.0--2496-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[vreset!](../cljs.core/vresetBANG.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2496"><img valign="middle" alt="[+] 0.0-2496" title="Added in 0.0-2496" src="https://img.shields.io/badge/+-0.0--2496-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[vswap!](../cljs.core/vswapBANG.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2496"><img valign="middle" alt="[+] 0.0-2496" title="Added in 0.0-2496" src="https://img.shields.io/badge/+-0.0--2496-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/when) <samp>→</samp></td>
<td><samp>[when](../cljs.core/when.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/when-first) <samp>→</samp></td>
<td><samp>[when-first](../cljs.core/when-first.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/when-let) <samp>→</samp></td>
<td><samp>[when-let](../cljs.core/when-let.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/when-not) <samp>→</samp></td>
<td><samp>[when-not](../cljs.core/when-not.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/when-some) <samp>→</samp></td>
<td><samp>[when-some](../cljs.core/when-some.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2261"><img valign="middle" alt="[+] 0.0-2261" title="Added in 0.0-2261" src="https://img.shields.io/badge/+-0.0--2261-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/while) <samp>→</samp></td>
<td><samp>[while](../cljs.core/while.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/with-meta)</td>
<td><samp>[with-meta](../cljs.core/with-meta.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/with-out-str)</td>
<td><samp>[with-out-str](../cljs.core/with-out-str.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1535"><img valign="middle" alt="[+] 0.0-1535" title="Added in 0.0-1535" src="https://img.shields.io/badge/+-0.0--1535-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/with-redefs)</td>
<td><samp>[with-redefs](../cljs.core/with-redefs.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1806"><img valign="middle" alt="[+] 0.0-1806" title="Added in 0.0-1806" src="https://img.shields.io/badge/+-0.0--1806-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[write-all](../cljs.core/write-all.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1503"><img valign="middle" alt="[+] 0.0-1503" title="Added in 0.0-1503" src="https://img.shields.io/badge/+-0.0--1503-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/zero?)</td>
<td><samp>[zero?](../cljs.core/zeroQMARK.md)</samp></td>
<td><samp>function/macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/zipmap)</td>
<td><samp>[zipmap](../cljs.core/zipmap.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/ASeq.java)</td>
<td><samp>[ASeq](../cljs.core/ASeq.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/Fn.java)</td>
<td><samp>[Fn](../cljs.core/Fn.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1552"><img valign="middle" alt="[+] 0.0-1552" title="Added in 0.0-1552" src="https://img.shields.io/badge/+-0.0--1552-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/Associative.java)</td>
<td><samp>[IAssociative](../cljs.core/IAssociative.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[IAtom](../cljs.core/IAtom.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2173"><img valign="middle" alt="[+] 0.0-2173" title="Added in 0.0-2173" src="https://img.shields.io/badge/+-0.0--2173-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/IChunk.java)</td>
<td><samp>[IChunk](../cljs.core/IChunk.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[IChunkedNext](../cljs.core/IChunkedNext.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/IChunkedSeq.java)</td>
<td><samp>[IChunkedSeq](../cljs.core/IChunkedSeq.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[ICloneable](../cljs.core/ICloneable.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2134"><img valign="middle" alt="[+] 0.0-2134" title="Added in 0.0-2134" src="https://img.shields.io/badge/+-0.0--2134-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[ICollection](../cljs.core/ICollection.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[IComparable](../cljs.core/IComparable.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/Counted.java)</td>
<td><samp>[ICounted](../cljs.core/ICounted.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/IDeref.java)</td>
<td><samp>[IDeref](../cljs.core/IDeref.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[IDerefWithTimeout](../cljs.core/IDerefWithTimeout.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/IEditableCollection.java)</td>
<td><samp>[IEditableCollection](../cljs.core/IEditableCollection.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[IEmptyableCollection](../cljs.core/IEmptyableCollection.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[IEncodeClojure](../cljs.core/IEncodeClojure.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1552"><img valign="middle" alt="[+] 0.0-1552" title="Added in 0.0-1552" src="https://img.shields.io/badge/+-0.0--1552-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[IEncodeJS](../cljs.core/IEncodeJS.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1552"><img valign="middle" alt="[+] 0.0-1552" title="Added in 0.0-1552" src="https://img.shields.io/badge/+-0.0--1552-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[IEquiv](../cljs.core/IEquiv.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/IFn.java)</td>
<td><samp>[IFn](../cljs.core/IFn.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-971"><img valign="middle" alt="[+] 0.0-971" title="Added in 0.0-971" src="https://img.shields.io/badge/+-0.0--971-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[IHash](../cljs.core/IHash.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/Indexed.java)</td>
<td><samp>[IIndexed](../cljs.core/IIndexed.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[IIterable](../cljs.core/IIterable.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2356"><img valign="middle" alt="[+] 0.0-2356" title="Added in 0.0-2356" src="https://img.shields.io/badge/+-0.0--2356-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[IKVReduce](../cljs.core/IKVReduce.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/IPersistentList.java)</td>
<td><samp>[IList](../cljs.core/IList.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/ILookup.java)</td>
<td><samp>[ILookup](../cljs.core/ILookup.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[IMap](../cljs.core/IMap.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/IMapEntry.java)</td>
<td><samp>[IMapEntry](../cljs.core/IMapEntry.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/IMeta.java)</td>
<td><samp>[IMeta](../cljs.core/IMeta.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[IMultiFn](../cljs.core/IMultiFn.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/Named.java)</td>
<td><samp>[INamed](../cljs.core/INamed.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[INext](../cljs.core/INext.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/IPending.java)</td>
<td><samp>[IPending](../cljs.core/IPending.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[IPrintWithWriter](../cljs.core/IPrintWithWriter.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1503"><img valign="middle" alt="[+] 0.0-1503" title="Added in 0.0-1503" src="https://img.shields.io/badge/+-0.0--1503-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/IRecord.java)</td>
<td><samp>[IRecord](../cljs.core/IRecord.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/IReduce.java)</td>
<td><samp>[IReduce](../cljs.core/IReduce.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[IReset](../cljs.core/IReset.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2173"><img valign="middle" alt="[+] 0.0-2173" title="Added in 0.0-2173" src="https://img.shields.io/badge/+-0.0--2173-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/Reversible.java)</td>
<td><samp>[IReversible](../cljs.core/IReversible.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/ISeq.java)</td>
<td><samp>[ISeq](../cljs.core/ISeq.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/Seqable.java)</td>
<td><samp>[ISeqable](../cljs.core/ISeqable.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/Sequential.java)</td>
<td><samp>[ISequential](../cljs.core/ISequential.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/IPersistentSet.java)</td>
<td><samp>[ISet](../cljs.core/ISet.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/Sorted.java)</td>
<td><samp>[ISorted](../cljs.core/ISorted.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/IPersistentStack.java)</td>
<td><samp>[IStack](../cljs.core/IStack.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[ISwap](../cljs.core/ISwap.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2173"><img valign="middle" alt="[+] 0.0-2173" title="Added in 0.0-2173" src="https://img.shields.io/badge/+-0.0--2173-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/ITransientAssociative.java)</td>
<td><samp>[ITransientAssociative](../cljs.core/ITransientAssociative.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/ITransientCollection.java)</td>
<td><samp>[ITransientCollection](../cljs.core/ITransientCollection.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/ITransientMap.java)</td>
<td><samp>[ITransientMap](../cljs.core/ITransientMap.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/ITransientSet.java)</td>
<td><samp>[ITransientSet](../cljs.core/ITransientSet.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/ITransientVector.java)</td>
<td><samp>[ITransientVector](../cljs.core/ITransientVector.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/IPersistentVector.java)</td>
<td><samp>[IVector](../cljs.core/IVector.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[IVolatile](../cljs.core/IVolatile.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2496"><img valign="middle" alt="[+] 0.0-2496" title="Added in 0.0-2496" src="https://img.shields.io/badge/+-0.0--2496-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[IWatchable](../cljs.core/IWatchable.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[IWithMeta](../cljs.core/IWithMeta.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[IWriter](../cljs.core/IWriter.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1503"><img valign="middle" alt="[+] 0.0-1503" title="Added in 0.0-1503" src="https://img.shields.io/badge/+-0.0--1503-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/ArrayChunk.java)</td>
<td><samp>[ArrayChunk](../cljs.core/ArrayChunk.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[ArrayIter](../cljs.core/ArrayIter.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[ArrayList](../cljs.core/ArrayList.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentHashMap.java)</td>
<td><samp>[ArrayNode](../cljs.core/ArrayNode.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[ArrayNodeSeq](../cljs.core/ArrayNodeSeq.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/Atom.java)</td>
<td><samp>[Atom](../cljs.core/Atom.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentHashMap.java)</td>
<td><samp>[BitmapIndexedNode](../cljs.core/BitmapIndexedNode.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentHashMap.java)</td>
<td><samp> └── [EMPTY](../cljs.core/BitmapIndexedNodeDOTEMPTY.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[BlackNode](../cljs.core/BlackNode.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/Box.java)</td>
<td><samp>[Box](../cljs.core/Box.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/ChunkBuffer.java)</td>
<td><samp>[ChunkBuffer](../cljs.core/ChunkBuffer.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/ChunkedCons.java)</td>
<td><samp>[ChunkedCons](../cljs.core/ChunkedCons.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentVector.java)</td>
<td><samp>[ChunkedSeq](../cljs.core/ChunkedSeq.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/Cons.java)</td>
<td><samp>[Cons](../cljs.core/Cons.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/Delay.java)</td>
<td><samp>[Delay](../cljs.core/Delay.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[ES6EntriesIterator](../cljs.core/ES6EntriesIterator.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2371"><img valign="middle" alt="[+] 0.0-2371" title="Added in 0.0-2371" src="https://img.shields.io/badge/+-0.0--2371-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[ES6Iterator](../cljs.core/ES6Iterator.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2371"><img valign="middle" alt="[+] 0.0-2371" title="Added in 0.0-2371" src="https://img.shields.io/badge/+-0.0--2371-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[ES6IteratorSeq](../cljs.core/ES6IteratorSeq.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2411"><img valign="middle" alt="[+] 0.0-2411" title="Added in 0.0-2411" src="https://img.shields.io/badge/+-0.0--2411-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[ES6SetEntriesIterator](../cljs.core/ES6SetEntriesIterator.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2371"><img valign="middle" alt="[+] 0.0-2371" title="Added in 0.0-2371" src="https://img.shields.io/badge/+-0.0--2371-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[Eduction](../cljs.core/Eduction.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2371"><img valign="middle" alt="[+] 0.0-2371" title="Added in 0.0-2371" src="https://img.shields.io/badge/+-0.0--2371-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentList.java)</td>
<td><samp>[EmptyList](../cljs.core/EmptyList.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/ExceptionInfo.java)</td>
<td><samp>[ExceptionInfo](../cljs.core/ExceptionInfo.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1576"><img valign="middle" alt="[+] 0.0-1576" title="Added in 0.0-1576" src="https://img.shields.io/badge/+-0.0--1576-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentHashmap.java)</td>
<td><samp>[HashCollisionNode](../cljs.core/HashCollisionNode.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/IndexedSeq.java)</td>
<td><samp>[IndexedSeq](../cljs.core/IndexedSeq.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[IndexedSeqIterator](../cljs.core/IndexedSeqIterator.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2371"><img valign="middle" alt="[+] 0.0-2371" title="Added in 0.0-2371" src="https://img.shields.io/badge/+-0.0--2371-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/APersistentMap.java)</td>
<td><samp>[KeySeq](../cljs.core/KeySeq.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1820"><img valign="middle" alt="[+] 0.0-1820" title="Added in 0.0-1820" src="https://img.shields.io/badge/+-0.0--1820-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/Keyword.java)</td>
<td><samp>[Keyword](../cljs.core/Keyword.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/LazySeq.java)</td>
<td><samp>[LazySeq](../cljs.core/LazySeq.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[LazyTransformer](../cljs.core/LazyTransformer.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp> └── [create](../cljs.core/LazyTransformerDOTcreate.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp> └── [createMulti](../cljs.core/LazyTransformerDOTcreateMulti.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentList.java)</td>
<td><samp>[List](../cljs.core/List.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentList.java)</td>
<td><samp> └── [EMPTY](../cljs.core/ListDOTEMPTY.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[MetaFn](../cljs.core/MetaFn.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2234"><img valign="middle" alt="[+] 0.0-2234" title="Added in 0.0-2234" src="https://img.shields.io/badge/+-0.0--2234-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/MultiFn.java)</td>
<td><samp>[MultiFn](../cljs.core/MultiFn.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[MultiStepper](../cljs.core/MultiStepper.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[NeverEquiv](../cljs.core/NeverEquiv.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentHashMap.java)</td>
<td><samp>[NodeSeq](../cljs.core/NodeSeq.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[ObjMap](../cljs.core/ObjMap.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp> └── [EMPTY](../cljs.core/ObjMapDOTEMPTY.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp> └── [HASHMAP_THRESHOLD](../cljs.core/ObjMapDOTHASHMAP_THRESHOLD.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp> └── [fromObject](../cljs.core/ObjMapDOTfromObject.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentArrayMap.java)</td>
<td><samp>[PersistentArrayMap](../cljs.core/PersistentArrayMap.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentArrayMap.java)</td>
<td><samp> └── [EMPTY](../cljs.core/PersistentArrayMapDOTEMPTY.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp> └── [HASHMAP-THRESHOLD](../cljs.core/PersistentArrayMapDOTHASHMAP-THRESHOLD.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp> └── [fromArray](../cljs.core/PersistentArrayMapDOTfromArray.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[PersistentArrayMapIterator](../cljs.core/PersistentArrayMapIterator.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2371"><img valign="middle" alt="[+] 0.0-2371" title="Added in 0.0-2371" src="https://img.shields.io/badge/+-0.0--2371-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[PersistentArrayMapSeq](../cljs.core/PersistentArrayMapSeq.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1820"><img valign="middle" alt="[+] 0.0-1820" title="Added in 0.0-1820" src="https://img.shields.io/badge/+-0.0--1820-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentHashMap.java)</td>
<td><samp>[PersistentHashMap](../cljs.core/PersistentHashMap.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentHashMap.java)</td>
<td><samp> └── [EMPTY](../cljs.core/PersistentHashMapDOTEMPTY.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp> └── [fromArray](../cljs.core/PersistentHashMapDOTfromArray.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2719"><img valign="middle" alt="[+] 0.0-2719" title="Added in 0.0-2719" src="https://img.shields.io/badge/+-0.0--2719-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp> └── [fromArrays](../cljs.core/PersistentHashMapDOTfromArrays.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentHashSet.java)</td>
<td><samp>[PersistentHashSet](../cljs.core/PersistentHashSet.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentHashSet.java)</td>
<td><samp> └── [EMPTY](../cljs.core/PersistentHashSetDOTEMPTY.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp> └── [fromArray](../cljs.core/PersistentHashSetDOTfromArray.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1443"><img valign="middle" alt="[+] 0.0-1443" title="Added in 0.0-1443" src="https://img.shields.io/badge/+-0.0--1443-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentQueue.java)</td>
<td><samp>[PersistentQueue](../cljs.core/PersistentQueue.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentQueue.java)</td>
<td><samp> └── [EMPTY](../cljs.core/PersistentQueueDOTEMPTY.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[PersistentQueueSeq](../cljs.core/PersistentQueueSeq.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentTreeMap.java)</td>
<td><samp>[PersistentTreeMap](../cljs.core/PersistentTreeMap.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentTreeMap.java)</td>
<td><samp> └── [EMPTY](../cljs.core/PersistentTreeMapDOTEMPTY.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[PersistentTreeMapSeq](../cljs.core/PersistentTreeMapSeq.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentTreeSet.java)</td>
<td><samp>[PersistentTreeSet](../cljs.core/PersistentTreeSet.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentTreeSet.java)</td>
<td><samp> └── [EMPTY](../cljs.core/PersistentTreeSetDOTEMPTY.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentVector.java)</td>
<td><samp>[PersistentVector](../cljs.core/PersistentVector.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1006"><img valign="middle" alt="[+] 0.0-1006" title="Added in 0.0-1006" src="https://img.shields.io/badge/+-0.0--1006-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentVector.java)</td>
<td><samp> └── [EMPTY](../cljs.core/PersistentVectorDOTEMPTY.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1006"><img valign="middle" alt="[+] 0.0-1006" title="Added in 0.0-1006" src="https://img.shields.io/badge/+-0.0--1006-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp> └── [EMPTY-NODE](../cljs.core/PersistentVectorDOTEMPTY-NODE.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp> └── [fromArray](../cljs.core/PersistentVectorDOTfromArray.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1006"><img valign="middle" alt="[+] 0.0-1006" title="Added in 0.0-1006" src="https://img.shields.io/badge/+-0.0--1006-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/APersistentVector.java)</td>
<td><samp>[RSeq](../cljs.core/RSeq.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/Range.java)</td>
<td><samp>[Range](../cljs.core/Range.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[RangeIterator](../cljs.core/RangeIterator.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2371"><img valign="middle" alt="[+] 0.0-2371" title="Added in 0.0-2371" src="https://img.shields.io/badge/+-0.0--2371-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[RangedIterator](../cljs.core/RangedIterator.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2371"><img valign="middle" alt="[+] 0.0-2371" title="Added in 0.0-2371" src="https://img.shields.io/badge/+-0.0--2371-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[RedNode](../cljs.core/RedNode.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/Reduced.java)</td>
<td><samp>[Reduced](../cljs.core/Reduced.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/SeqIterator.java)</td>
<td><samp>[SeqIter](../cljs.core/SeqIter.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[Stepper](../cljs.core/Stepper.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[StringBufferWriter](../cljs.core/StringBufferWriter.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1503"><img valign="middle" alt="[+] 0.0-1503" title="Added in 0.0-1503" src="https://img.shields.io/badge/+-0.0--1503-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[StringIter](../cljs.core/StringIter.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[Subvec](../cljs.core/Subvec.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/Symbol.java)</td>
<td><samp>[Symbol](../cljs.core/Symbol.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentArrayMap.java)</td>
<td><samp>[TransientArrayMap](../cljs.core/TransientArrayMap.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentHashMap.java)</td>
<td><samp>[TransientHashMap](../cljs.core/TransientHashMap.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentHashSet.java)</td>
<td><samp>[TransientHashSet](../cljs.core/TransientHashSet.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/PersistentVector.java)</td>
<td><samp>[TransientVector](../cljs.core/TransientVector.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[UUID](../cljs.core/UUID.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/APersistentMap.java)</td>
<td><samp>[ValSeq](../cljs.core/ValSeq.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1820"><img valign="middle" alt="[+] 0.0-1820" title="Added in 0.0-1820" src="https://img.shields.io/badge/+-0.0--1820-lightgrey.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](https://github.com/clojure/clojure/blob//src/jvm/clojure/lang/Var.java)</td>
<td><samp>[Var](../cljs.core/Var.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2496"><img valign="middle" alt="[+] 0.0-2496" title="Added in 0.0-2496" src="https://img.shields.io/badge/+-0.0--2496-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[VectorNode](../cljs.core/VectorNode.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[Volatile](../cljs.core/Volatile.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2496"><img valign="middle" alt="[+] 0.0-2496" title="Added in 0.0-2496" src="https://img.shields.io/badge/+-0.0--2496-lightgrey.svg"></a> </td>
</tr>
</table>

---

###### Symbols removed or no longer public:

 <table>
<thead><tr>
<th>=</th>
<th>Name</th>
<th>Type</th>
<th>History</th>
</tr></thead>
<tr>
<td></td>
<td><samp>[~~check-string-hash-cache~~](../cljs.core/check-string-hash-cache.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[+] 0.0-1424" title="Added in 0.0-1424" src="https://img.shields.io/badge/+-0.0--1424-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2261"><img valign="middle" alt="[×] 0.0-2261" title="Removed in 0.0-2261" src="https://img.shields.io/badge/×-0.0--2261-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[~~entries-iterator~~](../cljs.core/entries-iterator.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2268"><img valign="middle" alt="[+] 0.0-2268" title="Added in 0.0-2268" src="https://img.shields.io/badge/+-0.0--2268-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2371"><img valign="middle" alt="[×] 0.0-2371" title="Removed in 0.0-2371" src="https://img.shields.io/badge/×-0.0--2371-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[~~flatmap~~](../cljs.core/flatmap.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2341"><img valign="middle" alt="[×] 0.0-2341" title="Removed in 0.0-2341" src="https://img.shields.io/badge/×-0.0--2341-red.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/format)</td>
<td><samp>[~~format~~](../cljs.core/format.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1443"><img valign="middle" alt="[+] 0.0-1443" title="Added in 0.0-1443" src="https://img.shields.io/badge/+-0.0--1443-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1885"><img valign="middle" alt="[×] 0.0-1885" title="Removed in 0.0-1885" src="https://img.shields.io/badge/×-0.0--1885-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[~~iteration~~](../cljs.core/iteration.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2371"><img valign="middle" alt="[×] 0.0-2371" title="Removed in 0.0-2371" src="https://img.shields.io/badge/×-0.0--2371-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[~~iterator~~](../cljs.core/iterator.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2268"><img valign="middle" alt="[+] 0.0-2268" title="Added in 0.0-2268" src="https://img.shields.io/badge/+-0.0--2268-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2371"><img valign="middle" alt="[×] 0.0-2371" title="Removed in 0.0-2371" src="https://img.shields.io/badge/×-0.0--2371-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[~~pr-sequential~~](../cljs.core/pr-sequential.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[×] 0.0-1798" title="Removed in 0.0-1798" src="https://img.shields.io/badge/×-0.0--1798-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[~~pr-with-opts~~](../cljs.core/pr-with-opts.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1503"><img valign="middle" alt="[×] 0.0-1503" title="Removed in 0.0-1503" src="https://img.shields.io/badge/×-0.0--1503-red.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/printf)</td>
<td><samp>[~~printf~~](../cljs.core/printf.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1443"><img valign="middle" alt="[+] 0.0-1443" title="Added in 0.0-1443" src="https://img.shields.io/badge/+-0.0--1443-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1885"><img valign="middle" alt="[×] 0.0-1885" title="Removed in 0.0-1885" src="https://img.shields.io/badge/×-0.0--1885-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[~~set-entries-iterator~~](../cljs.core/set-entries-iterator.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2268"><img valign="middle" alt="[+] 0.0-2268" title="Added in 0.0-2268" src="https://img.shields.io/badge/+-0.0--2268-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2371"><img valign="middle" alt="[×] 0.0-2371" title="Removed in 0.0-2371" src="https://img.shields.io/badge/×-0.0--2371-red.svg"></a> </td>
</tr>
<tr>
<td>[<img width="18px" valign="middle" src="http://i.imgur.com/1GjPKvB.png">](http://clojure.github.io/clojure/branch-master/clojure.core-api.html#clojure.core/try)</td>
<td><samp>[~~try~~](../cljs.core/try.md)</samp></td>
<td><samp>macro</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1933"><img valign="middle" alt="[×] 0.0-1933" title="Removed in 0.0-1933" src="https://img.shields.io/badge/×-0.0--1933-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[~~unchecked-substract~~](../cljs.core/unchecked-substract.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2277"><img valign="middle" alt="[×] 0.0-2277" title="Removed in 0.0-2277" src="https://img.shields.io/badge/×-0.0--2277-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[~~unchecked-substract-int~~](../cljs.core/unchecked-substract-int.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[+] 0.0-1798" title="Added in 0.0-1798" src="https://img.shields.io/badge/+-0.0--1798-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2277"><img valign="middle" alt="[×] 0.0-2277" title="Removed in 0.0-2277" src="https://img.shields.io/badge/×-0.0--2277-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[~~vector-seq~~](../cljs.core/vector-seq.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1424"><img valign="middle" alt="[×] 0.0-1424" title="Removed in 0.0-1424" src="https://img.shields.io/badge/×-0.0--1424-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[~~IPrintable~~](../cljs.core/IPrintable.md)</samp></td>
<td><samp>protocol</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[×] 0.0-1798" title="Removed in 0.0-1798" src="https://img.shields.io/badge/×-0.0--1798-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[~~EntriesIterator~~](../cljs.core/EntriesIterator.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2268"><img valign="middle" alt="[+] 0.0-2268" title="Added in 0.0-2268" src="https://img.shields.io/badge/+-0.0--2268-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2371"><img valign="middle" alt="[×] 0.0-2371" title="Removed in 0.0-2371" src="https://img.shields.io/badge/×-0.0--2371-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[~~HashMap~~](../cljs.core/HashMap.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[×] 0.0-1798" title="Removed in 0.0-1798" src="https://img.shields.io/badge/×-0.0--1798-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp> └── [~~EMPTY~~](../cljs.core/HashMapDOTEMPTY.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[×] 0.0-1798" title="Removed in 0.0-1798" src="https://img.shields.io/badge/×-0.0--1798-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp> └── [~~fromArrays~~](../cljs.core/HashMapDOTfromArrays.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[×] 0.0-1798" title="Removed in 0.0-1798" src="https://img.shields.io/badge/×-0.0--1798-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[~~Iteration~~](../cljs.core/Iteration.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[+] 0.0-2301" title="Added in 0.0-2301" src="https://img.shields.io/badge/+-0.0--2301-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2371"><img valign="middle" alt="[×] 0.0-2371" title="Removed in 0.0-2371" src="https://img.shields.io/badge/×-0.0--2371-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[~~Iterator~~](../cljs.core/Iterator.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2268"><img valign="middle" alt="[+] 0.0-2268" title="Added in 0.0-2268" src="https://img.shields.io/badge/+-0.0--2268-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2371"><img valign="middle" alt="[×] 0.0-2371" title="Removed in 0.0-2371" src="https://img.shields.io/badge/×-0.0--2371-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp> └── [~~HASHMAP_THRESHOLD~~](../cljs.core/PersistentArrayMapDOTHASHMAP_THRESHOLD.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[×] 0.0-2301" title="Removed in 0.0-2301" src="https://img.shields.io/badge/×-0.0--2301-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp> └── [~~fromArrays~~](../cljs.core/PersistentArrayMapDOTfromArrays.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[+] 0.0-1211" title="Added in 0.0-1211" src="https://img.shields.io/badge/+-0.0--1211-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[×] 0.0-1798" title="Removed in 0.0-1798" src="https://img.shields.io/badge/×-0.0--1798-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp> └── [~~EMPTY_NODE~~](../cljs.core/PersistentVectorDOTEMPTY_NODE.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1006"><img valign="middle" alt="[+] 0.0-1006" title="Added in 0.0-1006" src="https://img.shields.io/badge/+-0.0--1006-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2301"><img valign="middle" alt="[×] 0.0-2301" title="Removed in 0.0-2301" src="https://img.shields.io/badge/×-0.0--2301-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[~~Set~~](../cljs.core/Set.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[×] 0.0-1211" title="Removed in 0.0-1211" src="https://img.shields.io/badge/×-0.0--1211-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp> └── [~~EMPTY~~](../cljs.core/SetDOTEMPTY.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1211"><img valign="middle" alt="[×] 0.0-1211" title="Removed in 0.0-1211" src="https://img.shields.io/badge/×-0.0--1211-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[~~SetEntriesIterator~~](../cljs.core/SetEntriesIterator.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2268"><img valign="middle" alt="[+] 0.0-2268" title="Added in 0.0-2268" src="https://img.shields.io/badge/+-0.0--2268-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-2371"><img valign="middle" alt="[×] 0.0-2371" title="Removed in 0.0-2371" src="https://img.shields.io/badge/×-0.0--2371-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp>[~~Vector~~](../cljs.core/Vector.md)</samp></td>
<td><samp>type</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[×] 0.0-1798" title="Removed in 0.0-1798" src="https://img.shields.io/badge/×-0.0--1798-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp> └── [~~EMPTY~~](../cljs.core/VectorDOTEMPTY.md)</samp></td>
<td><samp>var</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[×] 0.0-1798" title="Removed in 0.0-1798" src="https://img.shields.io/badge/×-0.0--1798-red.svg"></a> </td>
</tr>
<tr>
<td></td>
<td><samp> └── [~~fromArray~~](../cljs.core/VectorDOTfromArray.md)</samp></td>
<td><samp>function</samp></td>
<td><a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-927"><img valign="middle" alt="[+] 0.0-927" title="Added in 0.0-927" src="https://img.shields.io/badge/+-0.0--927-lightgrey.svg"></a> <a href="https://github.com/cljsinfo/cljs-api-docs/tree/0.0-1798"><img valign="middle" alt="[×] 0.0-1798" title="Removed in 0.0-1798" src="https://img.shields.io/badge/×-0.0--1798-red.svg"></a> </td>
</tr>
</table>

---

 <table>
<tr><td>
<img valign="middle" align="right" width="48px" src="http://i.imgur.com/Hi20huC.png">
</td><td>
Created for the upcoming ClojureScript website.<br>
[edit here] | [learn how]
</td></tr></table>

[edit here]:https://github.com/cljsinfo/cljs-api-docs/blob/master/cljsdoc/cljs.core.cljsdoc
[learn how]:https://github.com/cljsinfo/cljs-api-docs/wiki/cljsdoc-files