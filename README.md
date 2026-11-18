# Python Fundamentals - Assignment 3

This repository contains Python solutions for **Assignment 3**, covering fundamental programming concepts including `while` loops, loop control statements (`break`, `continue`, `else`), `for` loops with `range()`, and user-defined functions.

---

## 📋 Table of Contents
1. [Number Guessing Game](#1-number-guessing-game)
2. [Multiplication Table Generator](#2-multiplication-table-generator)
3. [BMI Calculator](#3-bmi-calculator)
4. [Prerequisites & Usage](#prerequisites--usage)

---

## 1. Number Guessing Game
**Concepts:** `while` loop, `random` module, `if-elif-else`, `continue`, `break`, and `while-else`.

### Description
A command-line guessing game where the program generates a random secret number between `1` and `10`. The user has **3 valid attempts** to guess the correct number.
* **Out-of-range guesses** (`< 1` or `> 10`) trigger a warning and use `continue` to skip deducting an attempt.
* **Correct guesses** congratulate the user and exit the loop immediately using `break`.
* **Exhausted attempts** trigger the `while-else` block to reveal the secret number.

### Sample Output
```text
Guess the number (between 1 and 10): 2
Too low. Try again.
Guess the number (between 1 and 10): 15
Your guess is out of range. Please guess a number between 1 and 10.
Guess the number (between 1 and 10): 5
Too high. Try again.
Guess the number (between 1 and 10): 3
Congratulations! You guessed the correct number.
```

---

## 2. Multiplication Table Generator
**Concepts:** `for` loop, `range()` function, formatted strings (f-strings).

### Description
Prompts the user for an integer and generates its standard multiplication table from `1` to `10`.

### Sample Output
```text
Enter the number for which you want the multiplication table: 5
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 x 5 = 25
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50
```

---

## 3. BMI Calculator
**Concepts:** User-defined functions, `return` statements, floating-point arithmetic, string formatting.

### Description
Defines a reusable function `calculate_bmi(weight, height)` that computes the Body Mass Index using the standard formula:

$$\text{BMI} = \frac{\text{weight (kg)}}{[\text{height (m)}]^2}$$

The program takes the user's weight and height as inputs and displays the calculated BMI rounded to two decimal places.

### Sample Output
```text
Enter your weight in kg: 58
Enter your height in meters: 1.62
Your BMI is: 22.10
```

---

## 🚀 Prerequisites & Usage

### Prerequisites
* **Python 3.x** installed on your system. No external libraries are required (uses only the built-in `random` module).

### Running the Scripts
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```
2. Run any of the Python scripts via your terminal:
   ```bash
   python filename.py
   ```