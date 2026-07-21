# Day 6 - Introduction to NumPy and Array Operations

## Objective

To understand the fundamentals of NumPy, create and manipulate arrays, perform indexing and slicing operations, explore array attributes, apply Boolean indexing, use built-in NumPy functions, and perform basic numerical computations for data analysis.

---

# Introduction

Today's session introduced **NumPy (Numerical Python)**, one of the most important libraries used in Data Science, Artificial Intelligence, and Machine Learning. NumPy provides high-performance multidimensional arrays and mathematical functions that enable efficient numerical computations.

The session focused on understanding NumPy arrays, their advantages over Python lists, array creation techniques, indexing, slicing, statistical operations, and practical applications commonly used during data preprocessing in machine learning.

---

# Topics Covered

## 1. Introduction to NumPy

Studied the purpose and advantages of NumPy.

Covered:

- What is NumPy?
- Importance in AI & Machine Learning
- Installing and importing NumPy
- Checking NumPy version
- Advantages over Python lists
- Faster mathematical computations
- Efficient memory management

Verified the installed NumPy version using:

- `np.__version__`

---

## 2. Creating NumPy Arrays

Learned different methods of creating arrays.

Implemented:

- Creating arrays from Python lists.
- One-dimensional arrays.
- Two-dimensional arrays.
- Converting lists into NumPy arrays.
- Creating arrays with specific data types using `dtype`.

Compared Python lists and NumPy arrays to observe differences in behavior and operations.

---

## 3. NumPy Built-in Array Creation Functions

Practiced commonly used array creation functions.

Covered:

### `np.zeros()`

Created arrays initialized with zeros.

---

### `np.ones()`

Generated arrays filled with ones.

---

### `np.arange()`

Created sequences using:

- Start value
- Stop value
- Step value

Generated even number sequences.

---

### `np.linspace()`

Generated evenly spaced values between two numbers.

Discussed its applications in plotting graphs and numerical computations.

---

### `np.eye()`

Created identity matrices.

Observed their importance in linear algebra and machine learning algorithms.

---

## 4. Array Attributes

Explored important NumPy array properties.

Studied:

- `ndim`
- `shape`
- `size`
- `dtype`
- `itemsize`

Learned how these attributes describe the structure and memory usage of arrays.

---

## 5. Array Indexing

Performed indexing operations on one-dimensional arrays.

Practiced:

- Positive indexing
- Negative indexing
- Updating array elements
- Accessing specific values

Modified array elements and verified changes.

---

## 6. Two-Dimensional Array Indexing

Created a 4×4 matrix using `np.zeros()`.

Performed:

- Accessing rows and columns
- Updating individual matrix elements
- Creating custom matrix patterns

Improved understanding of matrix indexing.

---

## 7. Array Slicing

Learned how to extract portions of arrays.

Practiced:

- Row slicing
- Column slicing
- Selecting submatrices
- Combining row and column slicing

Observed how slicing returns views of arrays.

---

## 8. Boolean Indexing

Introduced conditional filtering using Boolean expressions.

Implemented:

- Selecting elements greater than a given value.
- Selecting elements less than a specified value.
- Filtering arrays using logical conditions.

Learned how Boolean indexing simplifies data filtering.

---

## 9. Using `np.where()`

Studied conditional replacement of values.

Implemented a practical example to replace invalid salary values with corrected values using:

- `np.where(condition, true_value, false_value)`

Discussed its usefulness in data cleaning and preprocessing.

---

## 10. Statistical Operations

Performed statistical analysis using NumPy.

Calculated:

- Column-wise mean
- Row-wise mean

Used:

- `np.mean()`
- `axis = 0`
- `axis = 1`

Understood how axis selection changes computation.

---

## 11. Mathematical Operations on Arrays

Implemented element-wise arithmetic operations.

Example:

- Celsius to Fahrenheit temperature conversion.

Observed that NumPy performs calculations on the entire array without using loops.

---

## 12. Feature and Target Separation

Created a student dataset represented as a two-dimensional NumPy array.

Performed:

- Feature extraction
- Target variable extraction

Separated:

- Independent variables (Features)
- Dependent variable (Target)

Discussed how datasets are prepared before training Machine Learning models.

---

## Practical Work

During today's hands-on session:

- Installed and imported the NumPy library.
- Checked the installed NumPy version.
- Created one-dimensional and two-dimensional arrays.
- Converted Python lists into NumPy arrays.
- Created arrays using `zeros()`, `ones()`, `arange()`, `linspace()`, and `eye()`.
- Explored array attributes such as shape, size, dimensions, data type, and memory usage.
- Performed indexing and slicing on one-dimensional and two-dimensional arrays.
- Modified array elements using indexing.
- Applied Boolean indexing to filter data.
- Used `np.where()` for conditional data replacement.
- Calculated row-wise and column-wise averages.
- Converted temperature values from Celsius to Fahrenheit using vectorized operations.
- Prepared a dataset by separating features and target variables.
- Executed all programs with different datasets to verify outputs and understand NumPy operations.

---

## Outcome

Successfully gained a strong foundation in NumPy and understood how arrays simplify numerical computations. Learned array creation techniques, indexing, slicing, filtering, statistical operations, and data preprocessing methods that are essential for Data Science and Machine Learning workflows. Developed practical skills in handling structured numerical data efficiently using NumPy.

---


- Practical NumPy Exercises
- Introduction to Pandas
