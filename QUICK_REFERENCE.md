# AP Calculus BC Limits - Quick Reference Guide

## Essential Limit Formulas

### 1. Trigonometric Limits
```
lim (sin x)/x = 1    as x → 0
x→0

lim (1 - cos x)/x = 0    as x → 0
x→0

lim (tan x)/x = 1    as x → 0
x→0
```

### 2. Exponential and Logarithmic Limits
```
lim (e^x - 1)/x = 1    as x → 0
x→0

lim (1 + 1/x)^x = e    as x → ∞
x→∞

lim (ln(1 + x))/x = 1    as x → 0
x→0
```

### 3. L'Hôpital's Rule
**When to use:** Indeterminate forms 0/0 or ∞/∞

**Formula:**
```
If lim f(x)/g(x) is 0/0 or ∞/∞, then:
   x→a

lim f(x)/g(x) = lim f'(x)/g'(x)
x→a             x→a
```

**Important:** Check the form BEFORE applying!

### 4. Squeeze Theorem
**If:** g(x) ≤ f(x) ≤ h(x) for all x near a

**And:** lim g(x) = lim h(x) = L
        x→a       x→a

**Then:** lim f(x) = L
         x→a

## Problem-Solving Strategies

### Step 1: Try Direct Substitution
Always start by plugging in the value. If you get a real number, you're done!

### Step 2: Identify the Form
- **0/0** → Factor, conjugate, or L'Hôpital's Rule
- **∞/∞** → Divide by highest power or L'Hôpital's Rule
- **∞ - ∞** → Combine fractions or rationalize
- **0 · ∞** → Rewrite as a fraction
- **1^∞, 0^0, ∞^0** → Use logarithms

### Step 3: Choose Your Technique

#### For Rational Functions:
1. **Factor** numerator and denominator
2. **Cancel** common factors
3. **Substitute** again

#### For Limits at Infinity:
1. **Divide** by highest power of x
2. Terms with x in denominator → 0
3. **Simplify** what remains

#### For Trigonometric Limits:
1. Use **trig identities**
2. Manipulate to match **standard forms**
3. Apply **known limits**

#### For Radical Expressions:
1. **Multiply** by conjugate
2. **Simplify** using difference of squares
3. **Cancel** and substitute

## Common Indeterminate Forms

| Form | Example | Strategy |
|------|---------|----------|
| 0/0 | (x²-4)/(x-2) | Factor and cancel |
| ∞/∞ | (3x²)/(2x²+1) | Divide by highest power |
| 0·∞ | x·ln(x) as x→0⁺ | Rewrite as fraction |
| ∞-∞ | (x - √(x²+1)) | Rationalize |
| 1^∞ | (1+1/x)^x | Use e^(ln) |
| 0^0 | x^x as x→0⁺ | Use e^(ln) |
| ∞^0 | x^(1/x) as x→∞ | Use e^(ln) |

## Continuity Checklist

For f(x) to be continuous at x = a:

✅ **1. f(a) exists** (defined at a)

✅ **2. lim f(x) exists** (limit exists)
      x→a

✅ **3. lim f(x) = f(a)** (limit equals function value)
      x→a

### For Piecewise Functions:
- Check **left-hand limit**: lim f(x)
                            x→a⁻
- Check **right-hand limit**: lim f(x)
                              x→a⁺
- Verify: lim f(x) = lim f(x) = f(a)
         x→a⁻      x→a⁺

## AP Exam Tips

### What Graders Look For:
1. ✅ **Correct setup** of the problem
2. ✅ **Algebraic work** shown clearly
3. ✅ **Justification** of techniques used
4. ✅ **Proper notation** (limit notation, arrows)
5. ✅ **Final answer** clearly stated

### Common Point Deductions:
- ❌ Using L'Hôpital's Rule without checking form
- ❌ Canceling terms that aren't factors
- ❌ No justification for steps
- ❌ Arithmetic errors
- ❌ Not simplifying final answer

### Time Management:
- **Read** the entire problem first (30 sec)
- **Plan** your approach (30 sec)
- **Execute** with clear work (7-8 min)
- **Check** your answer (1 min)

## Practice Problem Checklist

Before moving to the next problem, ask yourself:

□ Did I try direct substitution first?
□ Did I identify the indeterminate form (if any)?
□ Did I show all algebraic steps?
□ Did I justify using L'Hôpital's Rule?
□ Did I check one-sided limits for piecewise functions?
□ Did I state my final answer clearly?
□ Does my answer make sense?

## Key Theorems to Remember

### Limit Laws:
- Sum/Difference: lim [f(x) ± g(x)] = lim f(x) ± lim g(x)
- Product: lim [f(x)·g(x)] = lim f(x) · lim g(x)
- Quotient: lim [f(x)/g(x)] = lim f(x) / lim g(x), if lim g(x) ≠ 0
- Power: lim [f(x)]^n = [lim f(x)]^n

### Composition:
If g is continuous at L and lim f(x) = L, then:
                           x→a
lim g(f(x)) = g(lim f(x)) = g(L)
x→a            x→a

## Calculator Usage

**When calculators ARE allowed:**
- Verify numerical limits
- Check your algebraic work
- Graph to understand behavior

**When calculators are NOT allowed:**
- Know your limit formulas cold
- Practice algebraic manipulation
- Memorize trig identities

---

## Quick Drill Problems

Try these without looking at solutions:

1. lim (x² - 9)/(x - 3) = ?
   x→3

2. lim sin(5x)/x = ?
   x→0

3. lim (3x² + 2x)/(5x² - 1) = ?
   x→∞

4. lim (e^x - 1)/x = ?
   x→0

**Answers:** 1) 6  2) 5  3) 3/5  4) 1

---

**Print this guide and keep it handy during practice sessions!**
