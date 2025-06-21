# 🗺️ Geographical Plotting with Plotly and Cufflinks

This folder contains notebooks related to **Geographical Data Visualization**, using libraries like Plotly, Cufflinks, and Pandas, as taught in the [Python for Data Science and Machine Learning Bootcamp by Jose Portilla](https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/).

## 📘 What Is Geographical Plotting?

Geographical plotting allows you to visualize **location-based data** directly on world maps or regional maps. In this section, we use **Plotly** and **Cufflinks** to create interactive choropleth maps that are especially useful for:

- Country-wise or state-wise metrics
- Time-based changes across geography
- Visual storytelling with spatial context

---

## 📂 Contents

| Notebook | Description |
|----------|-------------|
| `geographical_plotting.ipynb` | Choropleth maps using Plotly and Cufflinks with world and USA datasets |

---

## 🧠 Key Concepts Learned

- Introduction to `Plotly` and `Cufflinks` for interactive plotting
- Creating **choropleth maps** using `iplot()`
- Using built-in datasets for:
  - **World GDP per country**
  - **US Education data by state**
- Understanding how to use location, color scale, and data ranges in map plots
- Working with `locations`, `locationmode`, and color bars

---

## 🚀 Why It Matters

Geographical plotting is crucial for:
- Visualizing global or regional metrics
- Identifying patterns across countries or states
- Presenting data-driven insights in a visually engaging way

These visualizations are often used in:
- Public dashboards (e.g., COVID, population, income)
- Business analytics and marketing strategies
- Research involving geo-tagged data

---

## 🧪 Sample Code

```python
import plotly.express as px
import pandas as pd

df = pd.DataFrame({
    'Country': ['India', 'United States', 'China', 'Brazil'],
    'GDP': [2875, 21433, 14343, 1839]
})

fig = px.choropleth(df,
                    locations='Country',
                    locationmode='country names',
                    color='GDP',
                    color_continuous_scale='Blues',
                    title='Sample GDP by Country')

fig.show()
