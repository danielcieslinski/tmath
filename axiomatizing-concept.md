---
description: Novel way to stay formal and free, while speaking about daily life
cover: .gitbook/assets/ocean.jpg
coverY: 0
---

# Formalizing Concept

## Intuition

My motivation behind creating this formalisms. is so that, we don't have to waste time, for priorly specifying what we are exactly speaking about and overall, just making our lives easier when it comes to speaking about all kinds of ideas, where quantifiers like `never`, `all` cant be applied without losing formality to the system.

## Anti-concept

All concepts, have common exactly one common anti-concept. It is their <mark style="color:yellow;">non-existance</mark>. Given that every concept which doesn't exist is non-distinguishable and non-referancable(by a referencer of  higher specificity), there is exactly one anti-concept, that is common for all concepts.

The only rule is that it **must** **exist**. It can be non-referencable, or non-distinguishable. There are infintiely many concepts, that exist. Concepts, exist regardless of time, which is not obvious if we were to speak about `the idea` of something, because there is a point in time, from which we can say that it exists. Concept involves formal systems, that hold property of infinity-generating.

### Very important notes!

**Update** : This was, the inital idea, yet I provide handy realisation of this idea with use of Hilbert space and a function, acting as `quering function` in common computational sense. Where the argument to this function, is `contextualized descriptor`.

> Note: I leave the initial idea here, as I believe it's important to be able to see, how this idea evolved over time, what makes it easier to understand it, but also it allows reader to get the notion, of the purpose behind it, what is of superior value itself, but also, let's others to introduce suggestions, or corrections, to a final form, what is hard accomplish, when being presented a readymade formalism.

## Axioms of concept

Purpose of this formalism, was to extend the idea of thought, into scopes with different `meaning providers`.

* **Existence of concepts, is entirely independent from their descriptors.**

It can be illustrated with the idea, off as the meta Hilbert space. In other words: Whatever can be ever spoken off as a concept already exists in a this space, which contains, all concepts and so `definition` in context of a concept, instead of transforming framing object, should be thought off as accessing already existing element in that space.

## Meaning provider

### Intuition

Given the idea above, it obviously raises, the idea that same description, might represent something very different depending on who interprets the message.

> I use term `meaning provider` instead of what's commonly associated with word `interpreter` because word interpreter, associates descriptor, with specified schema, which is specifying how the meaning is inferred. Nevertheless. You can treat each other as aliases.

### **Contextualized descriptor**

Roughly speaking, it takes description of and returns object, which I call, `contextualized descriptor`, because it's a primer, to the `context` spanned along, with relevance, by value, up to its' anti-auto-morphism.

M(x) denotes translation(can be also thought of as convolution) of descriptor with `meaning` of x, provided by interpreter p, into singleton  <mark style="background-color:green;">concept Hilbert space</mark>, which is queryable space, common for all, meaning providers.

$$M_p(x) \rightarrow mpx$$ $$H_c(mpx) \rightarrow res | OT:C_s$$



#### Example

Let <mark style="color:green;">s</mark> be a concept descriptor. We can assume it's a string, in the computational sense.&#x20;

Let <mark style="color:blue;">Mx</mark> and <mark style="color:orange;">My</mark> My denote, two `meaning providers`. Each of them, maps sentence <mark style="color:green;">s</mark>, into sentences <mark style="color:blue;">mxs</mark> and <mark style="color:orange;">mys</mark>, which link to concepts that are associated with given descriptor(in this case sentence <mark style="color:green;">s</mark>) accordingly with the associated meaning.

## Identity of concepts

As mentioned, concepts exists, in singular Hilbert Space, accessible only by creating queries, pointing, to "regions"(or other varieties) that are relevant concept representations. Therefore identity of concepts, can be inferred, only by comparing.

* Therefore we can with no loss of generality, represent as function on the earlier mentioned Hilbert Space, which given sentences (<mark style="color:blue;">mxs,</mark> <mark style="color:orange;">mys)</mark><mark style="color:blue;">)</mark> return, appropriate association, that is simply. Hc(<mark style="color:blue;">mxs</mark>), Hc(<mark style="color:orange;">mys</mark>). Where Hc represents, <mark style="background-color:green;">the concept Hilbert space</mark>&#x20;

**Declarative definition of concepts identity**

```prolog
identity(meaning(x)):-(x)| meaning => [mxa, mxb] | ð = 0
```

To be interpreted as: **Concepts preserve their identity for specification x null difference of the contextualized descriptors **_**mxa  and**_**  **_**mxb.**_

It's dual to the expression **ð(Hc(ma), Hc(mb)) = 0**

## Semi-Abstracts&#x20;

#### Semi abstract X

Substitute X with any **formal object** which properties, you're interested in and here you go. You just created entirely new, formal object, that supports all those properties of X, which you need and none of those that you don't need. I call it the **semi-abstract trick**, it's a kind of a new way to stay formal and free :smile:

### Semi-abstract distance metric.

So the **only rule** is that, <mark style="background-color:red;">it has to be more of a distance metric, than no-distance metric.</mark> This is very useful, for describing and comparing objects, from completely disjoint contexts/scopes and omitting tones of irrelevant bullshit, that current understanding of formal concepts It's one of my favorite spell in fighting current mathematical establishment.

### Concepts, with realizers.

| Concept Descriptor                                                               | Realizer    | ∂: Semi-abstract distance metric |
| -------------------------------------------------------------------------------- | ----------- | -------------------------------- |
| A program, that provides an answer to the question: 'Whats' the meaning of life. | `print(42)` | ∂(c, r)                          |

**We say that object r is a perfect realizer** of formal concept `sc`, with semi-abstract distance metric ∂m, up to the degree of its formality.

**An example**

```python
sc = Concept("A program, that provides an answer to the question: What's meaning of life?")
r = 'The meaning of life is: {}'.format(get_answer(sc.question))

# This example is phenomental, because it illustrates, insanely growing, complexity, when trying to clearly define all the relevant ideas
```

`∂(sc, r)? -> val`

So in the first place it raises the question, what the hell is '∂' and the whole idea is that its' whatever you want it to be and it's formal up to the degree, of formality of your specification and the meaning As long, as you can provide non contradictory meaning, everything is cool.

### Formality

**Formality is just a property entirely dependent, on the knowledge of the meaning provider.** This should illustrate, that it's absolutely easy for what's said to be `formal object`, to contain errors disqualifying them entirely, from evaluation, which conditions its' `formality`. While still being able to stay a perfect realizer of this concept, to another meaning provider.

**Example: Syntax errors**

So I thought it's pretty problematic, because the idea of formality doesn't relate anything sensible anymore. And then I reminded, myself about my black magic and casted another `semi-abstract distance metric`, which this time happens to produce, all the distance metrics, which perfectly describe, all properties, of the mentioned system, as if by creating a gradient and corresponding mapping, to the annotated(labeled) relevance metric which is producing interpretable state-transition matrix, from which all information, considered relevant, can be directly interpreted.

_I hope it's the last time when I write such formal gibberish. Frameworks presented here, are capable of representing, all mathematical ideas, from which they derive, because they usually form a superset over, what they derive from, as composed, by non-assertive property selection, non-assertive beyond those, which itself are the desired property._

Therefore, generally speaking, they form `loss-free` formal system capable of describing all ideas, which, well, they are capable of describing ... **\[and up to its' anti-auto-morphism].**

{% content-ref url="other/chaos-generator.md" %}
[chaos-generator.md](other/chaos-generator.md)
{% endcontent-ref %}
