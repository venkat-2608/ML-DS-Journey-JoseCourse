# 📊 Matplotlib – Data Visualization with Python

This folder contains all notebooks and exercises related to **Matplotlib**, covered in the [Python for Data Science and Machine Learning Bootcamp by Jose Portilla](https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/).

## 📘 What is Matplotlib?

Matplotlib is the foundational plotting library in Python for **static, animated, and interactive visualizations**. It allows fine-grained control over every element in a plot.

---

## 📂 Contents

| Notebook | Description |
|----------|-------------|
| `matplotlib_intro.ipynb` | Basics of plotting: line, scatter, and bar plots |
| `matplotlib_customization.ipynb` | Plot styling, figure size, labels, titles, legends |
| `matplotlib_subplots.ipynb` | Creating multi-plot layouts with `plt.subplot()` and `plt.subplots()` |
| `matplotlib_exercises.ipynb` | Hands-on problems for visual understanding and practice |

---

## 🧠 Key Concepts Learned

- Plotting with `plt.plot()`, `plt.scatter()`, `plt.bar()`, etc.
- Labeling axes and adding titles/legends
- Creating and customizing subplots
- Adjusting figure size, color, line styles
- Saving plots to files (`.png`, `.jpg`, `.svg`)
- Gridlines and axis control

---

## 🚀 Why It Matters

Visualization is the most intuitive way to **understand your data**. Matplotlib is the backbone of visual analytics and is widely used in:

- Exploratory Data Analysis (EDA)
- Communicating insights from ML models
- Creating publication-quality figures

---

## 🧪 Sample Code

```python
import matplotlib.pyplot as plt

x = [1, 2, 3, 4]
y = [10, 20, 25, 30]

plt.plot(x, y, color='green', marker='o', linestyle='--')
plt.title('Sample Line Plot')
plt.xlabel('X Axis')
plt.ylabel('Y Axis')
plt.grid(True)
plt.show()
