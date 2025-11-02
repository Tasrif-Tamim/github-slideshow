# AP Calculus BC Limits - Practice Worksheet Answer Key

---

## Section A: Algebraic Limits

### Problem 1
**Answer: 6**

**Solution:**
$$\lim_{x \to 3} \frac{x^2 - 9}{x^2 - 5x + 6} = \lim_{x \to 3} \frac{(x-3)(x+3)}{(x-3)(x-2)} = \lim_{x \to 3} \frac{x+3}{x-2} = \frac{6}{1} = 6$$

---

### Problem 2
**Answer: 12**

**Solution:**
$$\lim_{x \to 2} \frac{x^3 - 8}{x - 2} = \lim_{x \to 2} \frac{(x-2)(x^2+2x+4)}{x-2} = \lim_{x \to 2} (x^2+2x+4) = 4+4+4 = 12$$

*Note: x³ - 8 = (x-2)(x²+2x+4) by sum/difference of cubes*

---

### Problem 3
**Answer: 1/4**

**Solution:**
$$\lim_{h \to 0} \frac{\sqrt{4+h} - 2}{h} \cdot \frac{\sqrt{4+h} + 2}{\sqrt{4+h} + 2} = \lim_{h \to 0} \frac{4+h-4}{h(\sqrt{4+h}+2)}$$
$$= \lim_{h \to 0} \frac{h}{h(\sqrt{4+h}+2)} = \lim_{h \to 0} \frac{1}{\sqrt{4+h}+2} = \frac{1}{4}$$

---

## Section B: Trigonometric Limits

### Problem 4
**Answer: 3**

**Solution:**
$$\lim_{x \to 0} \frac{\sin(3x)}{x} = \lim_{x \to 0} \frac{\sin(3x)}{3x} \cdot 3 = 3 \cdot 1 = 3$$

---

### Problem 5
**Answer: 2**

**Solution:**
$$\lim_{x \to 0} \frac{1-\cos(2x)}{x^2} = \lim_{x \to 0} \frac{2\sin^2(x)}{x^2}$$
Using identity: 1 - cos(2x) = 2sin²(x)
$$= 2 \lim_{x \to 0} \left(\frac{\sin x}{x}\right)^2 = 2(1)^2 = 2$$

---

### Problem 6
**Answer: 2**

**Solution:**
$$\lim_{x \to 0} \frac{\tan(4x)}{\sin(2x)} = \lim_{x \to 0} \frac{\sin(4x)}{\cos(4x) \cdot \sin(2x)}$$
$$= \lim_{x \to 0} \frac{\sin(4x)}{4x} \cdot \frac{2x}{\sin(2x)} \cdot \frac{4x}{2x \cos(4x)}$$
$$= 1 \cdot 1 \cdot \frac{4}{2 \cdot 1} = 2$$

---

## Section C: L'Hôpital's Rule

### Problem 7
**Answer: 2**

**Solution:**
(a) Direct substitution: (e⁰ - 1 - 0)/0² = 0/0 ✓ Indeterminate

(b) First application:
$$\lim_{x \to 0} \frac{2e^{2x} - 2}{2x} = \lim_{x \to 0} \frac{2(e^{2x}-1)}{2x}$$
Still 0/0, apply again:
$$\lim_{x \to 0} \frac{4e^{2x}}{2} = \frac{4}{2} = 2$$

(c) Final answer: **2**

---

### Problem 8
**Answer: 0**

**Solution:**
Form: ∞/∞, apply L'Hôpital's Rule:
$$\lim_{x \to \infty} \frac{\ln(x)}{x} = \lim_{x \to \infty} \frac{1/x}{1} = \lim_{x \to \infty} \frac{1}{x} = 0$$

---

### Problem 9
**Answer: 0**

**Solution:**
Rewrite as fraction:
$$\lim_{x \to 0^+} x \ln(x) = \lim_{x \to 0^+} \frac{\ln(x)}{1/x}$$
Form: -∞/∞, apply L'Hôpital's Rule:
$$= \lim_{x \to 0^+} \frac{1/x}{-1/x^2} = \lim_{x \to 0^+} \frac{x^2}{-x} = \lim_{x \to 0^+} (-x) = 0$$

---

## Section D: Limits at Infinity

### Problem 10
**Answer: 3/2**

**Solution:**
Divide by x³:
$$\lim_{x \to \infty} \frac{3 - 5/x + 7/x^3}{2 + 1/x^2 - 4/x^3} = \frac{3-0+0}{2+0-0} = \frac{3}{2}$$

---

### Problem 11
**Answer: 0**

**Solution:**
Divide by x³:
$$\lim_{x \to \infty} \frac{5/x + 3/x^2}{2 - 1/x^2} = \frac{0+0}{2-0} = 0$$

*Note: Numerator has lower degree than denominator*

---

### Problem 12
**Answer: -2**

**Solution:**
Multiply by conjugate:
$$\lim_{x \to \infty} (x - \sqrt{x^2+4x}) \cdot \frac{x + \sqrt{x^2+4x}}{x + \sqrt{x^2+4x}}$$
$$= \lim_{x \to \infty} \frac{x^2 - (x^2+4x)}{x + \sqrt{x^2+4x}} = \lim_{x \to \infty} \frac{-4x}{x + \sqrt{x^2+4x}}$$

Divide by x:
$$= \lim_{x \to \infty} \frac{-4}{1 + \sqrt{1+4/x}} = \frac{-4}{1+1} = -2$$

---

## Section E: Piecewise Functions and Continuity

### Problem 13

**(a) Answer: 4**

$$\lim_{x \to 2^-} \frac{x^2-4}{x-2} = \lim_{x \to 2^-} \frac{(x-2)(x+2)}{x-2} = \lim_{x \to 2^-} (x+2) = 4$$

**(b) Answer: 2a + b = 4**

For continuity: lim(x→2⁻) f(x) = lim(x→2⁺) f(x) = f(2)
- Left limit = 4
- Right limit = 2a + b
- f(2) = 2a + b

Therefore: **2a + b = 4** (any values satisfying this equation work)

**(c) Answer: b = -2**

If a = 3: 2(3) + b = 4 → 6 + b = 4 → **b = -2**

---

### Problem 14

**(a) Answer: 1 + k**

$$\lim_{x \to 1^-} g(x) = \lim_{x \to 1^-} (x^2 + k) = 1 + k$$

**(b) Answer: 5**

$$\lim_{x \to 1^+} g(x) = \lim_{x \to 1^+} (3x + 2) = 3(1) + 2 = 5$$

**(c) Answer: k = 4**

For continuity at x = 1:
$$1 + k = 5 \Rightarrow k = 4$$

**(d) Answer: Yes**

Both pieces are polynomials, which are continuous everywhere. With k = 4, the function is also continuous at x = 1 (the junction point). Therefore, g(x) is continuous everywhere.

---

## Section F: Special Limits

### Problem 15
**Answer: e⁶**

**Solution:**
$$\lim_{x \to \infty} \left(1 + \frac{3}{x}\right)^{2x} = \left[\lim_{x \to \infty} \left(1 + \frac{3}{x}\right)^{x/3}\right]^6$$

Let u = x/3:
$$= \left[\lim_{u \to \infty} \left(1 + \frac{1}{u}\right)^u\right]^6 = e^6$$

---

### Problem 16
**Answer: 0**

**Solution:**
Given: -x² ≤ f(x) ≤ x²

Find limits of bounds:
$$\lim_{x \to 0} (-x^2) = 0$$
$$\lim_{x \to 0} (x^2) = 0$$

By Squeeze Theorem: **lim(x→0) f(x) = 0**

---

### Problem 17
**Answer: 2**

**Solution:**
Method 1 (L'Hôpital's Rule):
Form: 0/0
$$\lim_{x \to 0} \frac{e^x - e^{-x}}{x} = \lim_{x \to 0} \frac{e^x + e^{-x}}{1} = 1 + 1 = 2$$

Method 2 (Limit properties):
$$\lim_{x \to 0} \frac{e^x - 1}{x} - \lim_{x \to 0} \frac{e^{-x} - 1}{x} = 1 - (-1) = 2$$

---

## Bonus Challenge

### Problem 18
**Answer: -1/6**

**Solution:**
Using L'Hôpital's Rule (form 0/0):

First application:
$$\lim_{x \to 0} \frac{\cos(x) - 1}{3x^2}$$
Still 0/0

Second application:
$$\lim_{x \to 0} \frac{-\sin(x)}{6x}$$
Still 0/0

Third application:
$$\lim_{x \to 0} \frac{-\cos(x)}{6} = \frac{-1}{6}$$

**Alternative:** Use Taylor series: sin(x) = x - x³/6 + ...
$$\lim_{x \to 0} \frac{(x - x^3/6 + ...) - x}{x^3} = \lim_{x \to 0} \frac{-x^3/6}{x^3} = -\frac{1}{6}$$

---

## Scoring Rubric

### Typical Point Distribution:
- **Correct setup**: 1 point
- **Algebraic work**: 2-3 points
- **Justification**: 1 point
- **Final answer**: 1 point

### Common Partial Credit:
- Correct method but arithmetic error: -1 point
- Missing justification: -1 point
- Incorrect simplification: -1 to -2 points

---

## Answer Summary

| Problem | Answer | Problem | Answer |
|---------|--------|---------|--------|
| 1 | 6 | 10 | 3/2 |
| 2 | 12 | 11 | 0 |
| 3 | 1/4 | 12 | -2 |
| 4 | 3 | 13a | 4 |
| 5 | 2 | 13b | 2a+b=4 |
| 6 | 2 | 13c | -2 |
| 7 | 2 | 14a | 1+k |
| 8 | 0 | 14b | 5 |
| 9 | 0 | 14c | 4 |
|   |   | 14d | Yes |
| 15 | e⁶ | 17 | 2 |
| 16 | 0 | 18 | -1/6 |

---

## Performance Guide

### Score Interpretation:
- **90-100**: Excellent! Ready for AP exam
- **80-89**: Very good, review missed concepts
- **70-79**: Good foundation, practice more
- **60-69**: Need more practice on weak areas
- **Below 60**: Review fundamentals, seek help

### Common Weak Areas:
If you struggled with:
- **Problems 1-3**: Review algebraic manipulation
- **Problems 4-6**: Study trig identities and limits
- **Problems 7-9**: Practice L'Hôpital's Rule
- **Problems 10-12**: Work on limits at infinity
- **Problems 13-14**: Focus on continuity concepts
- **Problems 15-17**: Review special limit forms

---

**Use this answer key to check your work and understand solution methods!**
