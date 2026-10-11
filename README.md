# 🐼 Pandas Basics

## 📌 About Pandas

Pandas is an open-source Python library used for **data manipulation, data cleaning, and data analysis**. It provides two main data structures: **Series (1D)** and **DataFrame (2D)**.

This repository contains notes and practical examples covering the fundamentals of Pandas.

## 📚 Table of Contents

* Introduction to Pandas
* Pandas Series
* Pandas DataFrame
* Data Inspection
* Data Cleaning
* Data Selection and Filtering
* Data Manipulation
* Installation
* Basic Example
* Learning Goals

## 🐍 Introduction to Pandas

* What is Pandas?
* Creating Series from lists and dictionaries
* Creating DataFrames from lists and dictionaries
* Reading CSV files using `read_csv()`

## 📊 Pandas Series

### Attributes

* `size`
* `dtype`
* `name`
* `is_unique`
* `index`
* `values`

### Methods

* `head()` and `tail()`
* `sample()`
* `value_counts()`
* `sort_values()`
* `sort_index()`

### Mathematical and Statistical Methods

* `count()`
* `sum()`
* `product()`
* `mean()`
* `median()`
* `mode()`
* `min()` and `max()`
* `describe()`

### Other Operations

* Series indexing and editing
* Python functions with Series
* Boolean indexing
* Plotting graphs using Series

## 🗂️ Pandas DataFrame

### Creating DataFrames

* Using lists
* Using dictionaries
* Reading CSV files

### Attributes

* `shape`
* `dtypes`
* `index`
* `columns`
* `values`

### Inspection Methods

* `head()` and `tail()`
* `sample()`
* `info()`
* `describe()`

### Data Cleaning

* `isnull()`
* `duplicated()`
* `rename()`
* `astype()`

### Data Selection

* Selecting single and multiple columns
* Selecting rows using `iloc` and `loc`
* Selecting rows and columns together
* Filtering DataFrames using conditions

### Data Manipulation

* Mathematical methods
* Adding new columns
* Creating columns from existing columns
* Changing data types

## ⚙️ Installation

Install Pandas:

```bash
pip install pandas
```

Install Matplotlib for data visualization:

```bash
pip install matplotlib
```

Import Pandas:

```python
import pandas as pd
```

## 💻 Basic Example

```python
import pandas as pd

data = {
    "Name": ["Aman", "Riya", "Rahul"],
    "Age": [21, 22, 20],
    "Marks": [85, 90, 78]
}

df = pd.DataFrame(data)

print(df.head())
print(df.describe())
print(df["Marks"].mean())
```

## 🎯 Learning Goals

* Understand Series and DataFrames.
* Learn data inspection, selection, and filtering.
* Practice data cleaning and manipulation.
* Build a foundation for Data Analysis and AI/ML.

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib

---

⭐ *A collection of Pandas notes, practice exercises, and hands-on coding examples.*

