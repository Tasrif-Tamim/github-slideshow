---
layout: slide
title: "FRQ 8: Solution"
---

## FRQ 8: Solution

**(a)** Recall: $\lim_{n \to \infty} \left(1 + \frac{1}{n}\right)^n = e$

Rewrite: $\left(1 + \frac{3}{x}\right)^{2x} = \left[\left(1 + \frac{3}{x}\right)^{x/3}\right]^6$

**(b)** Let u = x/3, as x → ∞, u → ∞:

$$\lim_{u \to \infty} \left[\left(1 + \frac{1}{u}\right)^u\right]^6 = e^6$$

**(c)** Let $y = \left(1 + \frac{3}{x}\right)^{2x}$, then $\ln y = 2x \ln\left(1 + \frac{3}{x}\right)$

$$\lim_{x \to \infty} \frac{\ln(1 + 3/x)}{1/(2x)} \stackrel{L'H}{=} \lim_{x \to \infty} \frac{-3/x^2}{1 + 3/x} \cdot \frac{-2x^2}{1} = 6$$

Therefore: $\lim y = e^6$
