# 📊 NumPy – Numerical Computing with Python

This folder contains all the notebooks and exercises related to **NumPy**, covered in the [Python for Data Science and Machine Learning Bootcamp by Jose Portilla](https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/).

## 📘 What is NumPy?

NumPy (Numerical Python) is the foundational Python library for performing numerical and matrix operations. It offers:

- Fast array operations
- Multi-dimensional arrays (`ndarray`)
- Mathematical, logical, and statistical functions
- Broadcasting and vectorization

---

## 📂 Contents

| Notebook | Description |
|----------|-------------|
| `numpy_intro.ipynb` | Basics of NumPy arrays, data types, and array creation |
| `numpy_operations.ipynb` | Element-wise operations, broadcasting, and comparison |
| `numpy_indexing.ipynb` | Indexing, slicing, and conditional selection |
| `numpy_array_methods.ipynb` | Useful array methods, reshaping, and more |
| `numpy_exercises.ipynb` | Practice problems to reinforce concepts |

---

## 🧠 Key Concepts Learned

- Creating arrays using `np.array()`, `np.arange()`, `np.linspace()`, etc.
- Array reshaping and dimensionality
- Indexing and slicing multi-dimensional arrays
- Arithmetic operations and broadcasting
- Logical filtering and conditional selection
- NumPy built-in functions like `np.mean()`, `np.std()`, `np.sum()`, etc.

---

## 🚀 Why It Matters

NumPy is the **core building block** for data analysis and machine learning workflows in Python. Libraries like Pandas, Scikit-learn, TensorFlow, and PyTorch are all built on top of NumPy concepts.

---

## 🧪 Sample Code

```python
import numpy as np

arr = np.arange(0, 10)
print(arr[arr % 2 == 0])  # Filter even numbers

matrix = np.random.rand(3, 3)
print(np.mean(matrix))    # Mean of all elements
