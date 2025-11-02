# AP Calculus BC Limits - Interactive Quiz

## Overview

This is an interactive command-line quiz application written in Ruby that helps students practice AP Calculus BC limit problems. The quiz asks questions and provides detailed explanations for each answer.

## Features

✨ **8 Comprehensive Questions** covering:
- Algebraic Limits (factoring, removable discontinuities)
- Trigonometric Limits (fundamental trig limits)
- L'Hôpital's Rule (multiple applications)
- Limits at Infinity (rational functions)
- Piecewise Functions & Continuity
- Squeeze Theorem
- Composite Functions
- Exponential Limits

✨ **Interactive Experience**:
- Multiple choice format (A/B/C/D)
- Immediate feedback after each question
- Detailed step-by-step explanations
- Score tracking and performance evaluation

✨ **Educational Value**:
- Mirrors AP Calculus BC exam style
- Emphasizes proper mathematical reasoning
- Provides justification for each step
- Covers all major limit topics

## Requirements

- Ruby 2.5 or higher

## How to Run

### Option 1: Direct Execution
```bash
ruby calculus_quiz.rb
```

### Option 2: Make it Executable
```bash
chmod +x calculus_quiz.rb
./calculus_quiz.rb
```

## How to Use

1. **Start the Quiz**: Run the script using one of the methods above
2. **Read Each Question**: Questions are presented one at a time with four options
3. **Enter Your Answer**: Type A, B, C, or D (case-insensitive)
4. **Review Explanation**: After each answer, you'll see whether you were correct and a detailed explanation
5. **Continue**: Press Enter to move to the next question
6. **View Results**: At the end, see your score and performance evaluation

## Example Session

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                              ║
║                        AP CALCULUS BC - LIMITS QUIZ                          ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝

Welcome to the AP Calculus BC Limits Interactive Quiz!

This quiz covers:
  • Algebraic Limits
  • Trigonometric Limits
  • L'Hôpital's Rule
  • Limits at Infinity
  • Piecewise Functions & Continuity
  • Squeeze Theorem
  • Composite Functions
  • Exponential Limits

You will be asked 8 questions.
For each question, enter your answer (A, B, C, or D).

Good luck! 📚✨

Press Enter to begin...


Question 1 of 8
================================================================================
CATEGORY: Algebraic Limits
================================================================================

Evaluate: lim(x→3) [(x² - 9)/(x² - 5x + 6)]

  A. The limit does not exist
  B. -6
  C. 6
  D. 0

Your answer (A/B/C/D): 
```

## Scoring

- **90-100%**: Excellent! Strong grasp of limits
- **75-89%**: Good job! On the right track
- **60-74%**: Keep practicing! Review concepts
- **Below 60%**: Don't give up! Study explanations carefully

## Topics Covered

### 1. Algebraic Limits
- Factoring techniques
- Removable discontinuities
- Indeterminate forms (0/0)

### 2. Trigonometric Limits
- Fundamental limit: lim(x→0) sin(x)/x = 1
- Algebraic manipulation with trig functions

### 3. L'Hôpital's Rule
- Identifying indeterminate forms
- Multiple applications
- Proper differentiation

### 4. Limits at Infinity
- Rational functions
- Horizontal asymptotes
- Leading coefficient method

### 5. Piecewise Functions
- One-sided limits
- Continuity conditions
- Solving for parameters

### 6. Squeeze Theorem
- Bounding functions
- Applying the theorem correctly

### 7. Composite Functions
- Limit laws for compositions
- Continuity requirements

### 8. Exponential Limits
- The number e
- Standard exponential limit forms

## Study Tips

1. **Try to solve each problem mentally first** before looking at the options
2. **Read the explanations carefully** even if you got the answer correct
3. **Take notes** on concepts you find challenging
4. **Retake the quiz** after studying to track improvement
5. **Practice showing all work** as required on the AP exam

## Code Structure

The quiz is built with two main classes:

- **Question**: Represents a single quiz question with options, correct answer, and explanation
- **Quiz**: Manages the collection of questions, scoring, and user interaction

## Customization

To add more questions, edit the `build_questions` method in the `Quiz` class and add new `Question` objects with:
- `question`: The problem statement
- `options`: Array of 4 answer choices
- `correct_answer`: The letter of the correct answer (A/B/C/D)
- `explanation`: Detailed step-by-step solution
- `category`: Topic category for organization

## License

This educational content is provided for AP Calculus BC exam preparation.

---

**Happy studying! Good luck on your AP Calculus BC exam! 🎓✨**
