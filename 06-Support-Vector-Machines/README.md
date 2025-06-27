# 🧭 Support Vector Machines (SVM) Projects

This folder includes two projects focused on **Support Vector Machines (SVMs)** — a powerful supervised machine learning algorithm used for classification tasks. These projects are part of my applied learning from Jose Portilla’s Machine Learning Bootcamp on Udemy.

---

## 📌 Project 1: SVM on Synthetic Data

### 🎯 Objective:
Classify a synthetically generated dataset with linear separation using SVM, and understand the role of hyperparameters like `C` and `gamma`.

### 🧪 Dataset:
Generated using `make_blobs()` from `sklearn.datasets`, consisting of two or more classes clearly separated in feature space.

### 🛠️ Key Concepts & Tools:
- `SVC` from `sklearn.svm`
- Visualizing decision boundaries with custom plotting functions
- Hyperparameter tuning using `C` (regularization) and `gamma` (influence range)
- Effects of underfitting vs overfitting based on these values

### 🧠 What I Practiced:
- Concept of maximum margin classifier
- How the kernel trick works for non-linear problems
- Model tuning for best generalization

---

## 🧬 Project 2: Cancer Classification with SVM

### 🎯 Objective:
Use SVM to predict whether a tumor is **malignant** or **benign** using clinical features.

### 📁 Dataset: `cancer.csv`  
Derived from the **Breast Cancer Wisconsin Diagnostic Database**, with features like:
- `radius_mean`, `texture_mean`, `area_mean`, etc.
- Target: `diagnosis` (M = malignant, B = benign)

### 🛠️ Key Steps:
- Performed EDA to understand feature distribution
- Preprocessed and scaled features with `StandardScaler`
- Trained an SVM model using `SVC`
- Evaluated using classification report, confusion matrix
- Tuned hyperparameters with `GridSearchCV`

### 🧠 What I Practiced:
- SVM with real-world medical data
- Importance of feature scaling in SVM
- Model optimization using grid search for better accuracy

---

## 🚀 What I Learned

- How SVMs classify data by maximizing the margin between classes
- How to handle both linear and non-linear classification problems using kernels
- Why proper **scaling** is crucial for distance-based classifiers like SVM
- How hyperparameters affect model performance

---

> ✅ Both of these projects were developed, explored, and documented by me as part of my core machine learning learning path. These help solidify how SVM works in both synthetic and real-world classification problems.
