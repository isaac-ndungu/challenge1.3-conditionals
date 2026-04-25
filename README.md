# Python Fundamentals — Core Programming Exercises

A collection of beginner-friendly Python programs covering core programming concepts such as loops, conditionals, user input handling, and basic algorithms — implemented in Jupyter Notebook.

## Overview

This project is a hands-on walkthrough of foundational Python programming concepts. Each section presents an isolated, interactive program that you can run and experiment with directly in Jupyter Notebook. All programs rely only on Python's standard library — no third-party packages required for the core logic.

---

## Features

### 1. Number Guessing Game
Generates a random number between 0 and 100. The player has **4 attempts** to guess correctly, receiving higher/lower hints after each wrong guess. Includes input validation to reject out-of-range values.

### 2.  Simple Calculator
Accepts two integers and an operator (`+`, `-`, `*`, `/`) from the user, performs the chosen operation, and displays the result. Handles invalid operator input gracefully.

### 3.  Prime Number Checker
Takes a number as input and determines whether it is a prime number using an efficient square-root-based algorithm.

### 4.  Multiplication Table Generator
Prints the full multiplication table (1 through 15) for any number entered by the user.

### 5.  Sum of a Number Range
Calculates and displays the sum of all integers from 1 up to a user-specified number.

### 6.  Star Pattern Printer
Prints an incrementally growing triangle of asterisks, adding one star per row up to the number specified by the user.

---

## Prerequisites

Make sure the following are installed on your system:

- Python 3.8 or higher
- `pip` (Python package manager)
- `git`

---

## Getting Started

### 1. Clone the Repository

```bash
git clone <repo_link>
cd your-repo-name
```

### 2. Create a Virtual Environment

**On macOS/Linux:**
```bash
python3 -m venv env
source venv/bin/activate
```

**On Windows:**
```bash
python -m venv env
venv\Scripts\activate
```

You should see `(env)` prefixed in your terminal once the environment is active.

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

> All exercises use Python's built-in modules only (`random`). The `requirements.txt` covers Jupyter Notebook itself.


Navigate to the `.ipynb` file and open it to begin.


---

## Usage

Open the notebook in Jupyter and run each section's cell individually. Every exercise is interactive — you will be prompted to enter values via `input()` fields directly in the notebook output.

Recommended approach:

- Run one cell at a time using **Shift + Enter**.
- Each section is independent, so you can run them in any order.
- To reset a section, go to **Kernel → Restart & Run All** to clear all outputs and start fresh.

> **Note:** Because several exercises use `input()`, make sure to complete each prompt before moving to the next cell, or the notebook may appear to hang while waiting for input.

---

> Built with Python 3 · Standard Library · Jupyter Notebook