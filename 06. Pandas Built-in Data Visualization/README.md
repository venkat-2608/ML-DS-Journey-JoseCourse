# 📊 Pandas Built-in Data Visualization

This folder contains notebooks related to **Pandas' built-in visualization tools**, as covered in the [Python for Data Science and Machine Learning Bootcamp by Jose Portilla](https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/).

## 📘 What Is It?

While Matplotlib and Seaborn are powerful visualization libraries, **Pandas itself integrates with Matplotlib** and provides simple, convenient ways to create basic plots directly from DataFrames and Series using `.plot()`.

---

## 📂 Contents

| Notebook | Description |
|----------|-------------|
| `pandas_visualization.ipynb` | Using `.plot()` to generate line, bar, hist, box, area, scatter, and pie charts |
| `pandas_visualization_examples.ipynb` | Hands-on usage with real datasets for built-in plots |

---

## 🧠 Key Concepts Learned

- Plotting Series and DataFrames using `.plot(kind='...')`
- Creating:
  - Line plots (default)
  - Bar and horizontal bar charts
  - Histograms
  - Area and Pie charts
  - Box plots and Scatter plots
- Plotting multiple columns
- Customizing size, labels, color, legend, and layout
- Integrating plots inside Jupyter Notebooks

---

## 🚀 Why It Matters

- You don’t always need to import Matplotlib or Seaborn for basic plots.
- Pandas plotting is quick for:
  - **Quick Exploratory Data Analysis (EDA)**
  - Dashboards and interactive data cleaning
- It's especially helpful during the initial stages of data analysis.

---

## 🧪 Sample Code

```python
import pandas as pd
import matplotlib.pyplot as plt

# Create dummy DataFrame
df = pd.DataFrame({
    'sales': [100, 120, 140, 180],
    'profit': [20, 30, 50, 70]
}, index=['Q1', 'Q2', 'Q3', 'Q4'])

# Plotting with Pandas
df.plot(kind='bar', figsize=(8,5), colormap='viridis', title='Quarterly Performance')
plt.ylabel('Amount')
plt.show()
