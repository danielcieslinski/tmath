---
description: Few handy lexical formalities
---

# Grammar

### General structure

I propose following simple grammar with the following general structure: `<Object A>` `{lexical functor} <Object B>.`Lexical functors which I use, are: $$\{OF, OV, OT\}$$

### Grammar specification

| Operand  | Target object |
| -------- | ------------- |
| `OV`     | Value         |
| `OF`     | Function      |
| `OT`     | Type          |

I guess it's best to explain it by the following example.&#x20;

```cpp
// Let X be a variable and for now let's assume that B is a complex object
// Assuming dot notation expression 

Expression: "X OV B" is equivalent to the 
val x = B.value

Expression: "X OF B" is equivalent to the 
function x = B.function

Expression: "X OF B" is equivalent to the 
type x = typeof(B)
```

The only difference to this code and the lexical framework I propose is that the expression is that in this grammar, expression are bidirectional.&#x20;

Simply there is no difference, between assigning and getting a value. `Performed operation` should be inferred from the context. If the value of the left hand object is unknown, then expression, can be understood as if assigning, to the object A, the value of the object B accordingly to the used lexical operator.
