# 🌳 Decision Tree & Random Forest Projects

This folder contains projects that apply **Decision Tree** and **Random Forest** classifiers — powerful supervised learning models used for both classification and regression. These projects are part of my hands-on learning from Jose Portilla’s ML course on Udemy.

---

## 🩻 Project 1: Kyphosis (Spinal Condition Classification)

### 📌 Objective:
Predict whether a patient has **kyphosis**, a spinal condition, based on age and vertebrae affected.

### 📁 Dataset: `kyphosis.csv`
- `Age`
- `Number` – Vertebrae number
- `Start` – Start position of the deformity
- `Kyphosis` (target: `present` or `absent`)

### ⚙️ Key Steps:
- Performed EDA with seaborn visualizations
- Trained a **Decision Tree Classifier**
- Visualized the decision tree structure using `graphviz` or `plot_tree`
- Evaluated performance using **Confusion Matrix** and **Classification Report**

### 🧠 What I Practiced:
- Interpreting decision tree splits
- Understanding overfitting risks in tree models

---

## 💰 Project 2: Loan Default Prediction (Decision Tree vs Random Forest)

### 📌 Objective:
Predict whether a person will **repay a loan** or **default** based on personal and financial data.

### 📁 Dataset: `loan_data.csv`
- Features include credit history, FICO score, income, purpose of loan, etc.
- Target: `not.fully.paid`

### ⚙️ Key Steps:
- Data cleaning and encoding categorical variables (`get_dummies`)
- Trained both a **Decision Tree Classifier** and a **Random Forest Classifier**
- Compared performance using accuracy, confusion matrix, classification report

### 🧠 What I Practiced:
- Difference between single trees and ensemble methods
- How Random Forest helps reduce overfitting
- Feature importance in tree-based models

---

## 🎯 What I Learned

- How to build and interpret decision trees
- The limitations of single decision trees
- How ensemble methods like **Random Forest** improve model robustness
- How to evaluate and compare tree models using classification metrics

---

> ✅ These projects are fully written, interpreted, and practiced by me during my ML learning journey. They reflect real use cases of decision-based classifiers and how they can be improved using ensemble techniques.
