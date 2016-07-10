---
name: cljs.core/>=
related:
  - cljs.core/>
---

## Signature
[x]
[x y]
[x y & more]


## Details

Returns true if each successive number argument is less than or equal to the
previous one, false otherwise.


## Examples

```clj
(>= 2 1)
;;=> true

(>= 2 2)
;;=> true

(>= 1 2)
;;=> false

(>= 6 5 4 3 2)
;;=> true
```