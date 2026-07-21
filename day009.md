# Day 9 - Data Selection, Filtering and Handling Missing Values in Pandas

## Objective

To learn different ways of selecting rows and columns in a Pandas DataFrame, perform filtering using Boolean indexing, understand data types, and handle missing values using different techniques.

---

# Introduction

Today's session focused on working with data inside a Pandas DataFrame. After learning how to create and load datasets, I learned how to select specific rows and columns, filter data based on conditions, and clean datasets containing missing values.

These operations are very important because before building any Machine Learning model, the dataset must be explored, filtered, and cleaned properly.

---

# Topics Covered

## 1. Selecting Columns

Learned different ways to select columns from a DataFrame.

Selected a single column using:

```python
df["Income"]
```

Observed that selecting one column returns a **Series**.

Also selected multiple columns using:

```python
df[["Age","Income"]]
```

Learned that selecting multiple columns returns a **DataFrame**.

Practiced selecting different combinations of columns.

---

## 2. Selecting Data using `.loc`

Learned how to access data using row labels and column names.

Practiced:

```python
df.loc[0:3,"CustomerID":"Income"]
```

Also selected specific columns using a list.

```python
cols=["CustomerID","Income"]
df.loc[0:3,cols]
```

Learned that `.loc` is mainly used when we know the row labels and column names.

---

## 3. Selecting Data using `.iloc`

Studied positional indexing.

Used:

```python
df.iloc[1:4,1:4]
```

Learned that:

- `.iloc` uses row and column positions.
- It is useful when we know the index numbers instead of column names.

Compared the difference between `.loc` and `.iloc`.

---

## 4. Storing Selected Data

Selected multiple rows and columns and stored them in another variable.

Example:

```python
cols=["Age","Purchased"]
row_record=df.loc[1:4,cols]
```

Learned that selected data can be stored and used later for analysis.

---

## 5. Boolean Indexing

Learned how to filter records using conditions.

Implemented:

```python
df[df["Income"]>50000]
```

Displayed only those records where income was greater than ₹50,000.

Discussed that filtering is commonly used while preparing datasets for Machine Learning.

---

## 6. Data Types in Pandas

Used:

```python
df.dtypes
```

to check the data type of every column.

Observed different data types such as:

- Integer
- Float
- Object (String)

Learned why understanding data types is important before performing analysis.

---

## 7. Changing Data Types

Converted the Income column into float type.

Used:

```python
df["Income"].astype("float64")
```

Learned that changing data types is useful for performing mathematical operations and preparing data for Machine Learning models.

---

## 8. Understanding Series and DataFrames

Compared:

### Series

- One-dimensional data.
- Represents a single column.

### DataFrame

- Two-dimensional table.
- Contains multiple rows and columns.

Observed the difference by checking their data types using `type()`.

---

## 9. Filtering Data Using Multiple Conditions

Learned that multiple conditions can be applied together using Boolean operators.

Studied:

- `&` (AND)
- `|` (OR)
- `~` (NOT)

Discussed how these operators help in selecting records based on multiple conditions.

---

## 10. Handling Missing Values

Introduced missing values in datasets.

Learned that missing values are represented as:

```text
NaN (Not a Number)
```

Discussed why missing values should be handled before training Machine Learning models.

---

## 11. Detecting Missing Values

Used:

```python
df.isnull().sum()
```

to check the total number of missing values in every column.

Learned how this function helps identify incomplete data.

---

## 12. Filling Missing Values

Studied one method of handling missing values.

Used:

```python
fillna()
```

Learned that missing values can be replaced with suitable values instead of deleting data.

Discussed that this technique is called **Imputation**.

---

## 13. Removing Missing Values

Learned another method of handling missing data.

Used:

```python
dropna()
```

Observed that rows containing missing values can be removed from the dataset.

Discussed situations where deleting rows is appropriate.

---

## Practical Work

During today's practical session, I:

- Selected individual columns from a DataFrame.
- Selected multiple columns together.
- Used `.loc` for label-based indexing.
- Used `.iloc` for position-based indexing.
- Retrieved specific rows and columns.
- Stored selected records into new variables.
- Filtered data using Boolean conditions.
- Displayed records based on income values.
- Checked data types using `dtypes`.
- Converted data types using `astype()`.
- Compared Series and DataFrames.
- Detected missing values using `isnull().sum()`.
- Learned different methods to handle missing values.
- Practiced using `fillna()` and `dropna()`.
- Executed all examples and verified the outputs.

---

## Applications in Data Science and Machine Learning

Today's concepts are widely used during:

- Data cleaning
- Data preprocessing
- Feature selection
- Dataset filtering
- Removing incomplete records
- Preparing data before training Machine Learning models
- Exploratory Data Analysis (EDA)

---

## Outcome

Today I learned how to work with datasets more efficiently using Pandas. I understood how to select rows and columns using different methods, filter records based on conditions, check and convert data types, and handle missing values using different techniques. These concepts are essential for cleaning and preparing datasets before performing any Machine Learning task.

---
