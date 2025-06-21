# 📈 Seaborn – Statistical Data Visualization in Python

This folder contains notebooks and exercises related to **Seaborn**, as covered in the [Python for Data Science and Machine Learning Bootcamp by Jose Portilla](https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/).

## 📘 What is Seaborn?

Seaborn is a powerful Python visualization library built on top of **Matplotlib**. It provides a high-level interface for creating **informative and attractive statistical graphics**.

---

## 📂 Contents

| Notebook | Description |
|----------|-------------|
| `seaborn_intro.ipynb` | Overview of Seaborn and setting up datasets |
| `seaborn_distribution_plots.ipynb` | Visualizing distributions: histograms, KDE plots, rug plots |
| `seaborn_categorical_plots.ipynb` | Bar plots, box plots, violin plots for categorical data |
| `seaborn_matrix_plots.ipynb` | Heatmaps and correlation matrices |
| `seaborn_grids.ipynb` | PairGrid, FacetGrid, JointGrid for multi-plot layouts |
| `seaborn_regression_plots.ipynb` | Regression visualization with `lmplot`, `regplot` |
| `seaborn_style_and_color.ipynb` | Styling, theming, and customizing Seaborn plots |
| `seaborn_exercises.ipynb` | Practice problems to reinforce visualization skills |

---

## 🧠 Key Concepts Learned

- Creating distribution plots (`distplot`, `histplot`, `kdeplot`)
- Categorical comparisons using box, violin, bar, and swarm plots
- Correlation heatmaps and pivot tables
- Visualizing relationships with scatter + regression
- Grids and subplots for grouped data visualization
- Customizing themes, color palettes, and styles

---

## 🚀 Why It Matters

Seaborn makes it easy to:

- Explore patterns in your data
- Identify trends and relationships
- Build EDA dashboards quickly and beautifully

It’s often the **preferred visualization library** for machine learning and data science projects.

---

## 🧪 Sample Code

```python
import seaborn as sns
import matplotlib.pyplot as plt

# Load built-in dataset
tips = sns.load_dataset('tips')

# Create a box plot of total bill by day
sns.boxplot(x='day', y='total_bill', data=tips, palette='coolwarm')

plt.title('Total Bill Distribution by Day')
plt.show()
