# 🐼 Pandas – Data Wrangling & Analysis with Python

This folder contains all notebooks and exercises related to **Pandas**, covered in the [Python for Data Science and Machine Learning Bootcamp by Jose Portilla](https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/).

## 📘 What is Pandas?

Pandas is the **go-to Python library for data analysis**. It provides fast, flexible, and expressive data structures like:

- **Series**: 1D labeled arrays
- **DataFrame**: 2D labeled data tables

It simplifies data cleaning, filtering, transformation, and analysis.

---

## 📂 Contents

| Notebook | Description |
|----------|-------------|
| `pandas_series.ipynb` | Introduction to Pandas Series (1D structures) |
| `pandas_dataframes.ipynb` | Creating, accessing, and modifying DataFrames |
| `pandas_selection.ipynb` | Selecting rows/columns using `.loc[]`, `.iloc[]`, conditions |
| `pandas_missing_data.ipynb` | Handling missing/null data (`NaN`) using `dropna()`, `fillna()` |
| `pandas_groupby.ipynb` | Aggregating and grouping data for summary statistics |
| `pandas_merge_join.ipynb` | Combining datasets using `merge()`, `join()`, `concat()` |
| `pandas_operations.ipynb` | Common operations: sorting, filtering, applying functions |
| `pandas_exercises.ipynb` | Practice problems to reinforce key concepts |

---

## 🧠 Key Concepts Learned

- Creating and manipulating `Series` and `DataFrames`
- Importing/exporting data from CSV, Excel, JSON, etc.
- Data filtering, slicing, and logical indexing
- Handling missing values
- Grouping and aggregating data
- Merging and joining multiple datasets
- Applying custom functions with `.apply()` and lambda

---

## 🚀 Why It Matters

Pandas is **essential** for every data science or ML project. It’s the tool used to:

- Clean raw datasets
- Perform Exploratory Data Analysis (EDA)
- Prepare data before feeding it into ML models

---

## 🧪 Sample Code

```python
import pandas as pd

df = pd.read_csv('data.csv')
print(df.head())

# Filtering rows where sales > 1000
filtered = df[df['sales'] > 1000]

# Group by region and calculate mean sales
print(df.groupby('region')['sales'].mean())
