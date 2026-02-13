# C# Fundamentals - Day 1 (ITI Track)


## Structure

The code is organized into **Regions** for better readability and logical separation:

### 1. Basics & Input/Output
- **Console I/O:** Reading strings and parsing integers using `int.Parse()`.
- **String Interpolation:** Using `$` to format output strings dynamically.
- **Escape Characters:** Handling special characters like `\n` (New Line) and `\t` (Tab).

### 2. String Literals
- **Verbatim Strings (`@`):** ignoring escape characters, useful for file paths and multi-line text.

### 3. Operators
A comprehensive coverage of C# operators:
- **Binary:** Basic arithmetic (`+`, `-`, `*`, `/`, `%`).
- **Unary:** Prefix (`++x`) vs Postfix (`x++`) increment/decrement operations.
- **Compound:** Simplified assignment operators (`+=`, `-=`).
- **Comparison:** Relational operators (`>`, `<`, `==`, `!=`) returning Boolean values.
- **Logical:** `&&` (AND) and `||` (OR) with Short-Circuit evaluation explanation.

### 4. Control Flow
Implementing decision-making logic:
- **If-Else Statements:** Handling conditions and nested logic.
- **Switch Case:** Organizing code for multiple discrete values (e.g., Job titles).

### 5. Loops (Iteration)
- **For Loop:** Iterating a specific number of times (e.g., printing based on name length).
- **Do-While:** Ensuring code runs at least once (e.g., Menu systems).
- **While Loop:** Checking conditions before execution (e.g., Summation with a specific limit).

### 6. Functions (Methods)
Demonstrating Local Functions inside `Main`:
- **Void Functions:** With and without parameters.
- **Return Functions:** Calculating values (e.g., Word count, String length) and returning results.

---

##  Lab & Exercises

![image](https://hackmd.io/_uploads/Skl1GI3vbg.png)


The project includes a `Lab 1` region containing practical problem-solving:

1.  **Arithmetic Logic:** Solving complex mathematical expressions respecting operator precedence.
2.  **Date Validation Algorithm:**
    - A custom function to validate dates.
    - Checks for day/month ranges.
    - **Leap Year Logic:** Handles February 29th validation correctly using `(Year % 4 == 0 && Year % 100 != 0) || (Year % 400 == 0)`.

---

