---
description: >-
  Unified notation and clarification representing numercial systems with
  different bases.
---

# Gates

### Purpose

Handy symbolic clarification of numerical expression in all numerical system

### Gate notation

$$n[g]$$denotes a gate.

In decimal system gate is denotes as $$n[5*2]$$. Using polish reverse notation$$n[2*2+1*2]$$.

Using additionally the operator language: $$n[*+*]$$is a gate of decimal numeric system. I'll later describe in more detailed way, how to convert from standard notation being something like $$10^n$$ into presented here, gated notation. I need to introduce before the idea of <mark style="background-color:blue;"><mark style="background-color:green;">3(Pr)s: Primer, product, property.<mark style="background-color:green;"></mark>

### Gating function

$$\overline{g}(...)$$is a gating function, or glueing function. It takes arguments, and glues them with the assigned gate.

$$ǥ:= n[*+*] | \overline{g}(a,b,...)$$ denotes a gating function, with a gate for decimal numerical system.

### Example

$$ǥ(1,2,3) = 123_{10}$$

### Conversion rules to gated version operator lang

* Sort expression having highest prime numbers on the left, smallest on the right.
* Calculate gcd? Shall I allow the base to be different that a primer of operator, ie 2? I'll come back to that.

### TODO

* [ ] Change n for lower index.
* [ ] Operator language.
