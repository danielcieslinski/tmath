---
description: Few handy lexical formalities
---

# Grammar

### General structure

I propose following simple grammar with the following general structure: `<Object A>` `{lexical functor} <Object B>.`Lexical operator which I use, are: $$\{OF, OV, OT\}$$

### Lexical operator

| Operand | Target object |
| ------- | ------------- |
| `OV`    | Value         |
| `OF`    | Function      |
| `OT`    | Type          |

I guess it's best to explain it by the following example.

```cpp
// Let X be a variable and for now let's assume that B is a complex object
// Assuming dot notation expression 

Expression: "X OV B" is equivalent to the 
val x <==> B.value

Expression: "X OF B" is equivalent to the 
function x <==> B.function

Expression: "X OT B" is equivalent to the 
type x <==> typeof(B)
```

In other words, **The lexical operator** accordingly to its kind {Value, Function, Type} creates bidirectional relationship between object A and B: `A <=(O{V, F, T})=> B`

### Sets

I use the following convection for typed set annotation. `<prefix>-set.`Where prefix is first letter of the according type. Abbreviations that I use, are expanded in the table below.

| Aliased | Expanded         |
| :-----: | ---------------- |
| `i-set` | Information set  |
| `f-set` | Set of functions |
| `o-set` | Set of objects.  |
