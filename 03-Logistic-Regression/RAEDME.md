# 🔐 Logistic Regression Projects

This folder contains two practical projects showcasing **Logistic Regression**, a powerful classification algorithm used to predict binary outcomes. These projects were completed as part of my hands-on practice while learning machine learning through Jose Portilla’s course on Udemy.

---

## 🚢 Project 1: Titanic Survival Prediction

### 📌 Objective:
Predict whether a passenger survived or not based on characteristics like age, sex, class, and family.

### 📁 Dataset: `titanic_train.csv`
- `Pclass` – Passenger class
- `Sex`
- `Age`
- `SibSp`, `Parch` – Siblings/Spouses, Parents/Children aboard
- `Fare`
- `Embarked`
- `Survived` (target)

### 🔧 Tools & Libraries:
- pandas, numpy
- seaborn, matplotlib
- sklearn: `train_test_split`, `LogisticRegression`, `metrics`
- `SimpleImputer`, `LabelEncoder`, `Pipeline`

### ⚙️ Steps Taken:
- Cleaned missing values (especially `Age` and `Cabin`)
- Handled categorical variables using `get_dummies`
- Split data and trained a **Logistic Regression model**
- Evaluated using **Confusion Matrix**, **Classification Report**, and **Accuracy Score**

---

## 📢 Project 2: Advertising Purchase Prediction

### 📌 Objective:
Predict whether a user clicked on an advertisement based on their browsing behavior and age/income.

### 📁 Dataset: `advertising.csv`
- `Daily Time Spent on Site`
- `Age`
- `Area Income`
- `Daily Internet Usage`
- `Clicked on Ad` (target)

### 🔧 Tools & Libraries:
- pandas, seaborn, matplotlib
- sklearn: `LogisticRegression`, `train_test_split`, `metrics`

### ⚙️ Steps Taken:
- Explored data distributions and relationships
- Checked correlation between features and the target
- Trained and tested a **Logistic Regression classifier**
- Evaluated with metrics like precision, recall, F1-score

---

## 🎯 What I Learned

- The mathematical intuition and application of **Logistic Regression**
- How to handle missing values and categorical variables
- How to evaluate classifiers using accuracy, precision, recall, F1-score
- Real-world decision-making in classification problems

---

> 💡 These projects solidified my understanding of binary classification using logistic regression and gave me confidence in handling real datasets with classification goals. All code, exploration, and interpretations are done by me during this learning journey.

