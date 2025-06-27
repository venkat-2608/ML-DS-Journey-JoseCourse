# 🔵 K-Means Clustering Projects

This folder contains projects that apply the **K-Means Clustering** algorithm — an unsupervised learning technique used to discover natural groupings in data. These projects were completed as part of my learning through Jose Portilla’s Machine Learning course on Udemy.

---

## 📌 Project 1: Synthetic Cluster Detection

### 🎯 Objective:
Use K-Means to identify distinct clusters in a synthetically generated dataset and compare with actual known labels.

### 🧪 Dataset:
Generated using `make_blobs()` from `sklearn.datasets`, with clearly defined cluster centers and labels.

### 🛠️ Key Concepts & Tools:
- `KMeans` from `sklearn.cluster`
- Visualizing cluster boundaries and centers
- Comparing predicted clusters vs actual labels
- Using the **Elbow Method** to determine optimal number of clusters (`k`)

### 🧠 What I Practiced:
- Core working of K-Means: centroid initialization, iteration, convergence
- Importance of choosing the correct value of `k`
- How K-Means can fail when clusters are not well-separated

---

## 🛍️ Project 2: Real-World Customer Segmentation

### 🎯 Objective:
Segment customers based on annual income and spending score to identify marketing strategies.

### 📁 Dataset: `Mall_Customers.csv` or similar
- Features:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

### 🛠️ Key Steps:
- Visualized data using pairplots and 2D scatter plots
- Removed irrelevant features like `CustomerID`
- Applied `KMeans` with different `k` values and used the **Elbow Method**
- Interpreted final clusters and business value behind them

### 🧠 What I Practiced:
- Applying clustering to business use-cases (e.g., customer profiling)
- Preprocessing and selecting features for better clustering
- Interpreting clusters beyond just labels — using plots and business logic

---

## 📚 What I Learned

- **K-Means** helps uncover hidden patterns in unlabeled data
- How to determine the optimal number of clusters using the **Elbow Method**
- Real-world clustering use-cases like market segmentation
- Limitations of K-Means (sensitivity to initial cluster centers, non-spherical data)

---

> ✅ These projects helped me understand the logic and applications of unsupervised learning through K-Means Clustering. All analysis and code were practiced and written by me.
