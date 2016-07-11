---
name: syntax/arg
display as: "% arg"
see also:
  - syntax/function
---

## Summary

## Details

Special vars for accessing implicit function arguments.

Only usable inside [doc:syntax/function].

- `%` or `%1` for first argument.
- `%2`, `%3` and so on for subsequent arguments
- `%&` for the rest of the arguments after the highest individually referenced argument

## Examples

```clj
(map #(* 2 %) [1 2 3])
;;=> (2 4 6)

(def f #(println %1 %2 %&))
(f 1 2 3 4 5)
;; prints: 1 2 (3 4 5)
```

<!-- AUTO-GENERATED docfile links for github -->
[doc:syntax/function]:https://github.com/cljs/api/blob/master/docfiles/syntax/function.md