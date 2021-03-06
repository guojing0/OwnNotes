---
layout: page
title: 单变量微积分（Single Variable Calculus）
---

### Derivation

* Product rule: \\( (fg)' = f'g + fg' \\)

* Quotient rule: \\( (\frac{g}{h})' = \frac{g'h - gh'}{h^2} \\)

* Chain rule: \\( (f\circ g)'(x) = g'(x)f'(g(x)) \\)

### Operations

* Composition: \\( f \circ(x) = f(g(x)) \\)

* Inverse: \\( f(f^{-1}(x)) = f^{-1}(f(x)) = x \\)

### The Exponential \\( e^{x} \\)

\\[ e^{x} = \sum_{k=0}^{\infty } \frac{x^{k}}{k!} \\]

### Properties of \\( e^{x} \\)

\\[ \frac{d}{dx}e^{x} = e^{x} \\]

\\[ \int e^{x}dx = e^{x} + C \\]

### Euler's formula

\\[ e^{ix} = \cos x + i \sin x \\]

\\[ \sin x =\sum_{k=0}^{\infty } (-1)^{k} \frac{x^{2k+1}}{(2k+1)!} \\]

\\[ \cos x = \sum_{k=0}^{\infty } (-1)^{k} \frac{x^{2k}}{(2k)!} \\]

### Taylor series at x = 0

Definition: \\( f(x) = \sum_{k=0}^{\infty } \frac{f^{k}(0)}{k!}x^{k} \\)

The coffcient: \\( c_{k} = \frac{f^{(k)}(0)}{k!} \\)

### Hyperbolic trig functions

\\[ sinh(x) = \frac{e^{x}-e^{-x}}{2} = \sum_{k=0}^{\infty } \frac{x^{2k+1}}{(2k+1)!} \\]

\\[ cosh(x) = \frac{e^{x}+e^{-x}}{2} = \sum_{k=0}^{\infty } \frac{x^{2k}}{(2k)!} \\]

\\[ tanh(x) = \frac{sinh(x)}{cosh(x)} = \frac{e^{x}-e^{-x}}{e^{x}+e^{-x}} \\]

\\[cosh^{2}(x) - sinh^{2}(x) = 1 \\]

\\[ \frac{d}{dx} sinh x = cosh x \\]
\\[ \frac{d}{dx} cosh x = sinh x \\]
