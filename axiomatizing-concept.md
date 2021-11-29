---
description: Novel way to stay formal and free, while speaking about daily life
cover: .gitbook/assets/ocean.jpg
coverY: 0
---

# Formalizing Concept

## Intution

My motivation behind creating this formalisms. is so that, we don't have to waste time, for priorly specifying what we are exactly speaking about and overall, just making our lifes easier when it comes to speaking about all kinds of ideas, where quantifiers like `never`, `all` cant be applied without losing formality to the system.

## Anti-concept

All concepts, have common exactly one common anti-concept. It is their <mark style="color:yellow;">non-existance</mark>. Given that every concept which doesn't exist is non-distinguishable and non-referancable(by a referencer of  higher specificity), there is exactly one anti-concept, that is common for all concepts.

The only rule is that it **must** **exist**. It can be non-referencable, or non-distinguishable. There are infintiely many concepts, that exist. Concepts, exist regardless of time, which is not obvious if we were to speak about `the idea` of something, because there is a point in time, from which we can say that it exists. Concept involves formal systems, that hold property of infinity-generating.

### Very important notes!

**Update** : This was, the inital idea, yet I provide handy realisation of this idea with use of Hilbert space and a function, acting as `quering function` in common computational sense. Where the argument to this function, is `contextualized descriptor`.

> Note: I leave the initial idea here, as I believe it's important to be able to see, how this idea evolved over time, what makes it easier to understand it, but also it allows reader to get the notion, of the purpose behind it, what is of superior value itself, but also, let's others to introduce suggestions, or corrections, to a final form, what is hard accomplish, when being presented a readymade formalism.

## Axiom of concept

Purpose of this formalism, was to extend the idea of thought, into scopes with different `meaning providers`.

* **Existance of concepts, is entirely independent from their descriptors.**

It can be illustrated with the idea, off as the meta Hillbert space. In other words: Whatever can be ever spoken off as a concept already exists in a this space, which contains, all concepts and so `definition` in context of a concept, instead of transforming framing object, should be thought off as accessing already existing element in that space.

## Meaning provider

### Intuition

Given the idea above, it obviously raises, the idea that same description, might represent something very different depending on who interprets the message.

> I use term `meaning provider` instead of what's commonly assosiated with word `interpreter` because word interpreter, assosiates descriptor, with specified schema, which is specifying how the meaning is infered. Nevertheless. You can treat each other as aliases.

### **Contextualized descriptor**

Roughly speaking, it takes description of and returns object, which I call, `contextalized descriptor`

> Because this concepts, is a primer, to the `context` spanned along, with relevance, by value, up to its' anti-auto-morphism.

denotes translation, of descriptor with `meaning` of $x$, for interpreter $p$, into common query space, common for all, meaning providers.

$$M_p(x) \rightarrow mpx$$ $$H_c(mpx) \rightarrow res | OT:C_s$$

## Identity of concepts

As said, concepts exists, in a space, accessible only by creating queries, pointing, to regions, or other varieties, that are relevant concept representations. Therefore identity of concepts, can be infered, only by comparing

**@TODO: Review needed**

* Let $s$ be a concept descriptor.
* Let $M\_x, M\_y$ denote, two `meaning providers`.
  * Each of them, map sentance $s$, into sentances $mxs$ and $mys$, which link to concepts that are assosiated with given descriptor(sentance $s$) accordingly with the local function.
* Therefore we can with no loss of generality, represent as function on the earlier mentioned Hilbert Space, which given sentances, $mxs, mys$ return, appropriete assosiation, that is simply. $H\_c(mxs), H\_c(mys)$

**Prolog-ish definition of concept identity**

```prolog
identity(meaning(x)):-(x)| meaning => [ma, mb] | ð = 0
```

To be interpreted as: **"Concepts preserve their identity for specification $x$ and contextualized\_descriptors $ma, mb$, for $ð(H\_c(ma), H\_c(mb))$ denoting divergence measurement, satisfies standardized binary relation "**

## Semi-Abstract $X$

Substitute $X$ with any **formal object** which properties, you're interested in and here you go. You just created entirely new, formal object, that supports all those properties of $X$, which you need and none of those that you don't need. I call it the **semi-abstract trick**, it's a kind of a new way to stay formal and free :)

## Semi-abstract metric

> Just a header. Go down. XD

## Semi-abstract distance metric.

So the only rule is that, it has to be more of a distance metric, than no-`distance` metric, templated above.

> This one, is super useful, for describing and comparing objects, from completly disjoint contexts/scopes and ommiting tones of irrelevant bullshit, that current understanding of formal concepts It's one of my favorite spell in fighting current mathematical estabilishement.

### Concepts, with realizers.

| Concept Descriptor                                                               | Realizer    | ∂: Semi-abstract distance metric |
| -------------------------------------------------------------------------------- | ----------- | -------------------------------- |
| A program, that provides an answer to the question: 'Whats' the meaning of life. | `print(42)` | ∂(c, r)                          |

**We say that object r is a perfect \_realiser**\_\*\* of formal concept sc, with semi-abstract distance metric ∂, up to the degree of its formality.\*\*

**An example**

```python
sc = Concept("A program, that provides an answer to the question: What's meaning of life?")
r = 'The meaning of life is: {}'.format(get_answer(sc.question))

# This example is phenomental, because it illustrates, insanely growing, complexity, when trying to clearly define all the relevant ideas
```

`∂(sc, r)? -> val`

So in the first place it raises the question, what the hell is '∂' and the whole idea is that its' whatever you want it to be and it's formal up to the degree, of formality of your specification and the meaning As long, as you can provide non contradictory meaning, everything is cool.

**Formality is just a property entirely dependent, on the knowledge of the meaning provider.** This should illustrate, that it's absolutely easy for what's said to be `formal object`, to contain errors disqualifying them entirely, from evaluation, which conditions its' `formality`. While still being able to stay a perfect realizer of this concept, to another meaning provider.

**Example: Syntax errors**

So I thought it's pretty problematic, because the idea of formality doesn't relate anything sensible anymore. And then I reminded, myself about my black magick and casted another `semi-abstract distance metric`, which this time happens to produce, all the distance metrics, which perfectly describe, all properties, of the mentioned system, as if by creating a gradient and corresponding mapping, to the annotated relevance metric which is producing interpretable state-transition matrix, from which all information, considered relevant, can be directly interpreted.

This is the last, time such bullshit has to be written. Frameworks presented here, are capable of representing, all mathematical ideas, from which they derive, because they usally form a superset over, what they derive from, as composed, by non-assertive property selection, non-assertive beyond those, which itself are the desired property.

Therefore, generally speaking, form, free of loss formal system capable of describing all ideas, which, well, they are capable of describing. **and up to its' morphism...**

Hower, it should not be the case. All those formalism, could be said as not formal, unless proven, i.e shown as holding desired properties for all edge case and unless they, are not formal or complete.

## Chaos generator(bonus that came up during the writing process)

This example is real gold, because, when we change $sc$. $r$ will generate all answers to the question, of purpose of life, that will be valid in this scope, yet never providing any statement, actually relevant to this question.

Let's suppose, of meaning of life, got into the last element in the set of all questions. Therefore the moment in which correct answer appears in the system, is the moment:

is translating set of all answers, into relevant. By this, correlating every answer, with the accordingly to belonging to the same set of answers, to which a correct answer belongs.

Therefore not only creating a mapping of each answer, to the binary value #false, upon the fact, of discovering, answer that is true.

While at the same time, each of those, should be decorelated. Because out-of their scope, from when we discovered the only true answer.

```python
res, q_list = [], list(*questions, Question('Whats meaning of life?')) 

for q in q_list:
    sc.question = q # Changes question
    res += r # Generates `wrong answer` to the question about the meaning of life, with an answer to another question.

# Damn, I don't have time for this, but seems like interesting example, super intuitive and powerful concerning concepts, of chaos.
# This updates system with an information, that basically triggers non-default behaviour, in the system state updates.
# Reminds, me off those dna chains, that lock  
```

**TODO**

* [ ] Finish example.
* [ ] Aggrgate and purify
* [ ] Concept box, frame containing all and only defined objects.
* [ ] Correcting examples.
