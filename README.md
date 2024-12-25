### Simple Calculator - OOP Java Project

This project, developed as part of the **CSE215 course (2020)**, implements a **simple calculator** with object-oriented programming principles in Java. Given the course's placement before the Data Structures and Algorithms (DSA) course, the calculator evaluates expressions linearly (left-to-right), rather than using advanced techniques like stack-based evaluation for mathematical expressions. 

---

### Key Features

#### 1. **Linear Expression Evaluation**
- Evaluates mathematical expressions from left to right.
- Automatically adds brackets to ensure valid syntax for all expressions.
- Prevents invalid inputs, such as:
  - Expressions starting with operators `+`, `/`, or `x` (with the exception of `-`).
  - Multiple consecutive `-` signs are interpreted as addition (`--` treated as `+`).
  - Numbers with more than one decimal point.

[![Demo: Linear Evaluation](http://img.youtube.com/vi/Gx-qJbisY_U/0.jpg)](http://www.youtube.com/watch?v=Gx-qJbisY_U)

---

#### 2. **Calculation History**
- Stores each calculation in a retrievable history binary objects.
- Previously computed results can be reloaded for future use.
- Includes classic calculator memory functions (MR, MS, MC, M+, M-). These are retained for compatibility, though made redundant by the history functionality.

[![Demo: Memory and History](http://img.youtube.com/vi/xvfq9D3KltQ/0.jpg)](http://www.youtube.com/watch?v=xvfq9D3KltQ)

---

#### 3. **Fractional Display**
- Results can be displayed as fractions.

[![Demo: Fractional Results](http://img.youtube.com/vi/FHVtatDG_ME/0.jpg)](http://www.youtube.com/watch?v=FHVtatDG_ME)

---

#### 4. **Sign Inversion**
- Allows inversion of the sign for the last entered number, simplifying operations on negative values.

[![Demo: Sign Inversion](http://img.youtube.com/vi/VWn_2DGSzVY/0.jpg)](http://www.youtube.com/watch?v=VWn_2DGSzVY)

---

#### 5. **Complex Number Arithmetic**
- Performs addition, subtraction, multiplication, and division of complex numbers.

[![Demo: Complex Number Operations](http://img.youtube.com/vi/dhsTeRe4QjQ/0.jpg)](http://www.youtube.com/watch?v=dhsTeRe4QjQ)

---

#### 6. **Quadratic Equation Solver**
- Solves quadratic equations.
- Handles cases with no real roots by providing solutions in terms of complex numbers.

[![Demo: Quadratic Solver](http://img.youtube.com/vi/b0JvYPcIoAs/0.jpg)](http://www.youtube.com/watch?v=b0JvYPcIoAs)

---

#### 7. **System of Equations Solver**
- Solves systems of linear equations efficiently.

[![Demo: System of Equations Solver](http://img.youtube.com/vi/rus-JsO8Tzg/0.jpg)](http://www.youtube.com/watch?v=rus-JsO8Tzg)

---

#### 8. **History Management**
- Allows deletion of individual history records.
- Includes an option to clear all history in one action.

[![Demo: History Management](http://img.youtube.com/vi/vZ2Kepe_lIA/0.jpg)](http://www.youtube.com/watch?v=vZ2Kepe_lIA)
