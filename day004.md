# Day 4 - Function Arguments, Variable Scope, Recursion and List Operations

## Objective

To explore different types of function arguments in Python, understand variable scope, implement recursive functions, and learn fundamental list operations along with solving practical programming problems.

---

# Introduction

Today's session focused on enhancing the understanding of Python functions by learning different ways to pass arguments and manage variables. The session also introduced recursion, one of the important programming techniques used in algorithm design. Towards the end, an introduction to Python lists and their commonly used operations was covered through multiple hands-on examples.

These concepts are widely used in Artificial Intelligence and Machine Learning while designing reusable functions, preprocessing datasets, handling collections of data, and implementing algorithms.

---

# Topics Covered

## 1. Types of Function Arguments

Learned various ways of passing data to functions.

### Positional Arguments

- Arguments are passed according to the order of parameters.
- The position of each value determines which parameter receives it.
- Implemented examples using multiple parameters.

---

### Default Arguments

Studied how default values can be assigned to function parameters.

Practiced:
- Calling functions without passing every argument.
- Overriding default values when required.
- Simplifying function calls using default parameters.

---

### Keyword Arguments

Learned how keyword arguments improve readability.

Implemented examples where:
- Arguments were passed using parameter names.
- Order of arguments became independent.
- Default values were modified using keywords.

---

### Variable Length Arguments (`*args`)

Studied how a function can accept any number of positional arguments.

Implemented:
- Expense calculator using `*args`.
- Calculated total expenses using the built-in `sum()` function.
- Observed that `*args` stores values as a tuple.

---

### Keyword Variable Length Arguments (`**kwargs`)

Learned how functions can accept multiple keyword arguments.

Implemented an example to store machine learning model hyperparameters such as:

- Learning Rate
- Batch Size
- Dropout

Used dictionary traversal with `.items()` to display each parameter and its value.

---

## 2. Variable Scope

Studied the scope of variables inside and outside functions.

Topics covered:

### Local Variables

- Variables declared inside a function.
- Accessible only within that function.

### Global Variables

- Variables declared outside functions.
- Accessible throughout the program.

### Global Keyword

Learned how the `global` keyword allows modification of global variables from inside a function.

Implemented examples to observe changes before and after function execution.

---

## 3. Recursive Functions

Introduced recursion as a technique where a function calls itself until a stopping condition is reached.

### Factorial Program

Implemented recursive logic to calculate factorial of a number.

Concepts understood:

- Base Case
- Recursive Case
- Recursive function calls

Tested the program using different input values.

---

### Fibonacci Series

Implemented Fibonacci number generation using recursion.

Observed:

- Recursive execution flow
- Previous function calls contributing to current results
- Importance of the base condition

---

## 4. Introduction to Python Lists

Learned about Python's list data structure.

Covered:

- Creating lists
- Accessing elements
- Mutable nature of lists
- Storing multiple values in a single variable

---

## 5. List Operations

Practiced commonly used list methods.

### Adding Elements

- `append()`
- `extend()`
- `insert()`

---

### Removing Elements

- `remove()`
- `pop()`

---

### Accessing Data

Practiced:

- Positive indexing
- Negative indexing
- List slicing
- Step slicing

---

### Sorting Lists

Implemented sorting using:

- `sort()`
- `sort(reverse=True)`
- `sorted()`

Compared the difference between list methods and built-in functions.

---

### Built-in Functions with Lists

Used:

- `max()`
- `len()`

Performed operations on numerical datasets.

---

### Updating List Elements

Modified salary values using loops.

Implemented calculations to update each element of the list based on a percentage deduction.

---

## 6. Practical Problem Solving

Implemented several real-world programming exercises.

### Expense Calculator

Created a reusable function using `*args` to calculate the total expenditure.

---

### Machine Learning Hyperparameter Display

Designed a function using `**kwargs` to display configurable model parameters dynamically.

---

### Factorial Calculator

Implemented recursion to compute factorial values for different numbers.

---

### Fibonacci Generator

Generated Fibonacci numbers recursively.

---

### Outlier Handling

Worked with a prediction dataset containing invalid values (`-99.0`).

Implemented logic to identify and remove outlier values from the list.

Discussed how such preprocessing techniques are useful in machine learning datasets.

---

### Two Sum Problem

Solved a common interview problem.

Objective:
- Find pairs of numbers whose sum equals 11.
- Avoid duplicate pairs.
- Used additional lists (`visited`) to efficiently track processed elements.

Generated unique pairs satisfying the required condition.

---

## Practical Work

During today's session:

- Implemented user-defined functions with different argument types.
- Practiced positional, keyword, default, variable-length, and keyword variable-length arguments.
- Created reusable functions for mathematical and logical operations.
- Explored local and global variable behavior.
- Implemented recursive programs for factorial and Fibonacci series.
- Performed multiple list operations including insertion, deletion, sorting, slicing, and indexing.
- Updated list elements using loops.
- Solved practical programming problems such as Expense Calculator, Hyperparameter Configuration, Outlier Removal, and the Two Sum Problem.
- Executed every program with multiple test cases to verify correctness and understand program flow.

---

## Outcome

Successfully understood advanced concepts of Python functions, argument passing techniques, variable scope, recursion, and list manipulation. Strengthened problem-solving skills by implementing multiple practical programs and gained confidence in writing modular and reusable Python code.

---

