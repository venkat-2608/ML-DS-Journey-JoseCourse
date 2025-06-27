# 🤝 K Nearest Neighbors (KNN) Projects

This folder contains projects that implement the **K-Nearest Neighbors (KNN)** classification algorithm — a non-parametric method used for classification and regression. These exercises helped reinforce my understanding of KNN from Jose Portilla’s machine learning course.

---

## 🗂️ Project 1: Classified Data (KNN on Scaled Features)

### 📌 Objective:
Train a KNN model on synthetic classified data and evaluate its performance.

### 📁 Dataset: `Classified Data.csv`
- This dataset is artificially generated with a clear decision boundary.
- Target: `TARGET CLASS`

### ⚙️ Key Steps:
- Applied **StandardScaler** to scale the feature values
- Split data into training and testing sets
- Used `KNeighborsClassifier` from sklearn
- Evaluated model using **Confusion Matrix**, **Classification Report**
- Used a **for loop** to determine the best `k` (Elbow Method)

### 🧠 What I Practiced:
- Why feature scaling is essential for KNN
- Choosing the right `k` value
- Model performance comparison across different `k` values

---

## 📦 Project 2: KNN Project Data

### 📌 Objective:
Apply KNN to a more realistic dataset and interpret its predictions.

### 📁 Dataset: `KNN_Project_Data.csv`
- This dataset mimics a real-world scenario with more features and noise
- Target: `TARGET CLASS`

### ⚙️ Key Steps:
- Cleaned and prepared the data
- Scaled all features using `StandardScaler`
- Trained the KNN model
- Evaluated model using classification metrics
- Identified optimal `k` value using the Elbow Method again

### 🧠 What I Practiced:
- Feature scaling and its impact on distance-based algorithms
- How KNN performs with more complex data
- Trade-off between bias and variance in KNN

---

## 🧠 What I Learned

- KNN is a simple yet powerful algorithm when features are properly scaled
- Choosing the correct value of `k` is crucial to avoid overfitting or underfitting
- Real-world datasets often need more preprocessing
- Importance of standardization in distance-based models

---

> ✅ All code, analysis, and interpretations in these notebooks are done by me while practicing and understanding KNN algorithm during my ML learning journey.
