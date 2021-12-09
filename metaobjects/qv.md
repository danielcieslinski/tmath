---
description: One concept for all
---

# QV

## Polymorphism

| Q                   | Inside object | V(value)                    |
| ------------------- | :-----------: | --------------------------- |
| \*                  |    {i-set}    | \*                          |
| {querying function} |     object    | {assert, result}            |
| {qualifier}(target) |     object    | validator: {comparable}     |
| {quality}           |      ...      | VS: {comparable & numeric}  |

V(Validator) can be set of bools, while when Q=quality, then boolean is not an option. It must be higher order comparable, that is numeric.&#x20;

```
// Some code

let x = Object(*params)
qxv = QV(x)

Set.add(o)
Q(S, x) | x in? S => always #yes  
```
