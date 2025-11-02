# 🎓 AP Calculus BC Limits Quiz - Quick Start Guide

## What Is This?

An **interactive command-line quiz** that asks you 8 AP Calculus BC limit questions and provides detailed step-by-step answers. Perfect for exam preparation!

---

## 🚀 How to Run (3 Simple Steps)

### Step 1: Make sure Ruby is installed
```bash
ruby --version
```
If you see a version number (e.g., `ruby 2.7.0`), you're good to go! ✅

If not, install Ruby:
- **macOS**: `brew install ruby` (or use built-in Ruby)
- **Ubuntu/Debian**: `sudo apt-get install ruby`
- **Windows**: Download from [ruby-lang.org](https://www.ruby-lang.org/en/downloads/)

### Step 2: Run the quiz
```bash
ruby calculus_quiz.rb
```

### Step 3: Answer the questions!
- Read each question carefully
- Type your answer: **A**, **B**, **C**, or **D**
- Press **Enter**
- Read the detailed explanation
- Continue to the next question

---

## 📚 What You'll Practice

### 8 Questions Covering:

1. **Algebraic Limits** - Factoring and simplifying
2. **Trigonometric Limits** - Using sin(x)/x = 1
3. **L'Hôpital's Rule** - Handling indeterminate forms
4. **Limits at Infinity** - Rational functions
5. **Piecewise Functions** - Continuity conditions
6. **Squeeze Theorem** - Bounding functions
7. **Composite Functions** - Limit composition
8. **Exponential Limits** - The number e

---

## 📖 Example Question

```
================================================================================
CATEGORY: Trigonometric Limits
================================================================================

Evaluate: lim(x→0) [sin(3x)/x]

  A. 0
  B. 1
  C. 3
  D. The limit does not exist

Your answer (A/B/C/D): C
```

**✓ CORRECT! Well done!**

**EXPLANATION:**
```
Step 1: Recognize this is related to lim(x→0) [sin(x)/x] = 1
Step 2: Rewrite: sin(3x)/x = 3 · [sin(3x)/(3x)]
Step 3: Let u = 3x, as x→0, u→0
Step 4: This becomes: 3 · lim(u→0) [sin(u)/u]
Step 5: Apply the fundamental limit: 3 · 1 = 3

The answer is 3.
```

---

## 🎯 Scoring

- **90-100%** (7-8 correct): 🌟 **EXCELLENT!** Strong grasp of limits
- **75-89%** (6 correct): 👍 **GOOD JOB!** On the right track
- **60-74%** (5 correct): 📖 **KEEP PRACTICING!** Review concepts
- **Below 60%** (≤4 correct): 💪 **DON'T GIVE UP!** Study more

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `calculus_quiz.rb` | Main quiz application (run this!) |
| `QUIZ_README.md` | Detailed documentation |
| `QUIZ_SUMMARY.md` | Complete overview of features |
| `SAMPLE_QUIZ_SESSION.md` | Full walkthrough with all Q&A |
| `QUIZ_QUICK_START.md` | This file - quick start guide |

---

## 💡 Study Tips

1. **Try to solve mentally first** before looking at options
2. **Read explanations even if correct** - learn alternative methods
3. **Take notes** on challenging concepts
4. **Retake the quiz** to track improvement
5. **Show all work** on paper as practice for the AP exam

---

## 🔧 Troubleshooting

### "ruby: command not found"
→ Ruby is not installed. See Step 1 above.

### "Permission denied"
→ Make the file executable: `chmod +x calculus_quiz.rb`

### Quiz won't start
→ Make sure you're in the correct directory: `cd /path/to/quiz`

---

## 📊 All Questions at a Glance

| # | Topic | Correct Answer |
|---|-------|----------------|
| 1 | Algebraic Limits | B. -6 |
| 2 | Trigonometric Limits | C. 3 |
| 3 | L'Hôpital's Rule | C. 2 |
| 4 | Limits at Infinity | B. 3 |
| 5 | Piecewise Functions | C. k = 3 |
| 6 | Squeeze Theorem | B. 0 |
| 7 | Composite Functions | C. 8 |
| 8 | Exponential Limits | B. e³ |

*(See `SAMPLE_QUIZ_SESSION.md` for full solutions)*

---

## 🎓 Ready to Start?

```bash
ruby calculus_quiz.rb
```

**Good luck on your AP Calculus BC exam! 📚✨**

---

## 📝 Need More Help?

- **Full Documentation**: Read `QUIZ_README.md`
- **Complete Walkthrough**: See `SAMPLE_QUIZ_SESSION.md`
- **Feature Overview**: Check `QUIZ_SUMMARY.md`

---

*Created for AP Calculus BC exam preparation*
