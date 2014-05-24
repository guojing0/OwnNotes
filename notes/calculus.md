---
layout: page
title: 单变量微积分（Single Variable Calculus）
---

### Derivation

* Product rule: \\( (fg)' = f'g + fg' \\)

* Quotient rule: if \\( f(x) = \frac{g(x)}{h(x)} \\) then \\( \frac{d}{dx}f(x) = f'(x) = \frac{g'(x)h(x) - g(x)h'(x)}{{h(x)}^2} \\)

* Chain rule: \\( (f\circ g)'(x) = g'(x)f'(g(x)) \\)

### Operations

* Composition: \\( f \circ(x) = f(g(x)) \\)

* Inverse: \\( f(f^{-1}(x)) = f^{-1}(f(x)) = x \\)

### The Exponential \\( e^{x} \\)

\\[ e^{x} = \sum_{k=0}^{\infty } \frac{x^{k}}{k!} \\]

### Properties of \\( e^{x} \\)

* \\[ \frac{d}{dx}e^{x} = e^{x} \\]
* \\[ \int e^{x}dx = e^{x} + C \\]

### Euler's formula

\\[ e^{ix} = \cos x + i \sin x \\]

\\[ \sin x =\sum_{k=0}^{\infty } \frac{x^{2k+1}}{(2k+1)!} \\]

\\[ \cos x = \sum_{k=0}^{\infty } \frac{x^{2k}}{(2k)!} \\]

### Taylor series at x = 0

Definition: \\( f(x) = \sum_{k=0}^{\infty } \frac{f^{k}(0)}{k!}x^{k} \\)

The coffcient \\( c_{k} \\): c_{k} = \\( \frac{f^{(k)}(0)}{k!} \\)