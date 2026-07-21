# Day 8 - Introduction to Pandas

## Objective

To understand the basics of the Pandas library, learn about its main data structures (Series and DataFrame), create DataFrames, read datasets from CSV files, and explore datasets using different Pandas functions.

---

# Introduction

Today I started learning **Pandas**, one of the most important libraries in Python for Data Science and Machine Learning. Before today, I had worked with Python lists and NumPy arrays. Pandas makes working with large datasets much easier because it stores data in rows and columns, just like an Excel sheet.

I learned that Pandas is built on top of NumPy, so it is fast and efficient while also providing many extra features for handling real-world datasets. Almost every Data Science and Machine Learning project uses Pandas for reading, cleaning, organizing, and analyzing data.

---

# Topics Covered

## 1. Installing and Importing Pandas

The session started with installing the Pandas library and importing it into Python.

Used:

```python
import pandas as pd
import numpy as np
```

I also learned why we use `pd` as an alias for Pandas and `np` for NumPy.

---

## 2. Introduction to Pandas

Learned about the purpose of Pandas and why it is widely used.

Discussed:

- Data analysis
- Data manipulation
- Reading datasets
- Cleaning datasets
- Working with rows and columns
- Handling missing values
- Preparing datasets for Machine Learning

Also understood that Pandas can work with many file formats such as:

- CSV
- Excel
- JSON
- SQL databases

---

## 3. NumPy Array

Created a NumPy array using a Python list.

```python
list1 = [10,20,30,40]
arr = np.array(list1)
```

Observed:

- The array stores numerical values efficiently.
- NumPy arrays contain elements of the same data type.
- Arrays support fast mathematical operations.

Checked the data type using:

```python
type(arr)
```

---

## 4. Pandas Series

Created a Series from the same list.

```python
series1 = pd.Series(list1)
```

Learned that:

- A Series is a one-dimensional data structure.
- Every value has its own index.
- It behaves like a single column of a table.
- Series can store numbers, strings, and other data types.

Compared the output of a NumPy array and a Pandas Series to understand their differences.

---

## 5. DataFrame

Created a DataFrame using a Python dictionary.

Example columns:

- Name
- Course
- Roll Number

Observed that:

- A DataFrame contains multiple rows and columns.
- Different columns can have different data types.
- DataFrames are the most commonly used structure in Pandas.

Displayed the complete DataFrame to understand its tabular format.

---

## 6. DataFrame Shape

Used:

```python
df.shape
```

to find:

- Total number of rows.
- Total number of columns.

Learned how this helps in understanding the size of a dataset.

---

## 7. Reading CSV Files

Learned how to load external datasets into Python.

Used:

```python
df = pd.read_csv("data.csv")
```

Displayed the dataset after loading it successfully.

This is one of the most commonly used functions in Data Science because most datasets are stored in CSV format.

---

## 8. Exploring the Dataset

Practiced different Pandas functions to understand the contents of a dataset.

### `df.info()`

Used to:

- View column names.
- Check data types.
- Count non-null values.
- Understand the overall structure of the dataset.

---

### `df.head()`

Displayed the first few rows of the dataset.

Useful for quickly checking whether the data has been loaded correctly.

---

### `df.tail()`

Displayed the last few rows of the dataset.

Helpful for viewing the ending records.

---

### `df.describe()`

Generated statistical information such as:

- Count
- Mean
- Standard Deviation
- Minimum Value
- Maximum Value
- Quartiles

Learned that this function is very useful for understanding numerical data.

---

### `df.columns.to_list()`

Converted all column names into a Python list.

This is useful when selecting or processing columns in larger datasets.

---

## 9. Difference Between Lists, NumPy and Pandas

Compared three different ways of storing data.

### Python Lists

- Flexible
- Easy to create
- Slower for large datasets

### NumPy Arrays

- Faster calculations
- Efficient memory usage
- Same data type throughout the array

### Pandas

- Stores data in rows and columns.
- Supports multiple data types in different columns.
- Easy to analyze and manipulate datasets.
- Provides many built-in functions for data analysis.

---

## Practical Work

During today's practical session, I performed the following activities:

- Installed the Pandas library.
- Imported both NumPy and Pandas.
- Created NumPy arrays from Python lists.
- Created a Pandas Series.
- Compared NumPy arrays with Pandas Series.
- Created a DataFrame using a dictionary.
- Displayed the DataFrame.
- Checked the shape of the DataFrame.
- Loaded a CSV file using `read_csv()`.
- Displayed the complete dataset.
- Viewed dataset information using `info()`.
- Displayed the first and last records using `head()` and `tail()`.
- Generated summary statistics using `describe()`.
- Retrieved all column names using `columns.to_list()`.
- Compared Python Lists, NumPy Arrays, and Pandas DataFrames.

---

## Applications in Data Science and Machine Learning

Discussed how Pandas is used in real-world projects for:

- Reading datasets
- Cleaning data
- Handling missing values
- Data preprocessing
- Feature selection
- Data transformation
- Exploratory Data Analysis (EDA)
- Preparing datasets before training Machine Learning models

---

## Outcome

By the end of today's session, I understood the basics of Pandas and its importance in Data Science. I learned how to create Series and DataFrames, load datasets from CSV files, inspect datasets using different functions, and compare Pandas with Python lists and NumPy arrays. I also gained practical experience in organizing and exploring tabular data, which will be useful in future Machine Learning projects.

---
