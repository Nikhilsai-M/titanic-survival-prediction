# 🛳️ Titanic Survival Prediction

This repository contains a complete walkthrough of solving the **Titanic survival prediction** problem using machine learning. The task is based on Kaggle’s famous [Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic) competition.

---

## 🎯 Objective

Predict whether a passenger survived or not based on features such as:

- Age
- Gender
- Class
- Fare
- Siblings/Spouses Aboard
- Parents/Children Aboard
- Embarked location
- Titles extracted from names

---

## 📊 Exploratory Data Analysis (EDA)

Performed extensive EDA to understand:

- Survival rate by gender, age group, and passenger class
- Distribution of fares and age
- Missing data patterns
- Correlations and insights to guide feature selection

---

## 🧠 Feature Engineering

Engineered new features to improve model performance:

- **Title extraction** from names (Mr., Miss, etc.)
- **Family size** from SibSp + Parch
- **IsAlone** indicator
- **Age bands** using binning
- **Fare bands** 

---

## 🤖 Models Used

Built and evaluated the following models:

- Logistic Regression
- Single Vector Machine(SVM)
- KNearestNeighbors
- SGD Classifier
- Decision tree
- Random Forest Classifier (with GridSearchCV)
- XGBoost Classifier (with tuned parameters)

All models were evaluated using validation score.
Final model (Random Forest) is evaluated using accuracy,precision ,recall and confusion matrix.

---

## 🏁 Final Model

The best model was a **Random Forest Classifier** with optimized hyperparameters using `GridSearchCV`.

- **Leaderboard Score on Kaggle**: `0.78468`

---

## 🔧 Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

---

## 🗂 Files in This Repository

- `titanic-survival-prediction.ipynb` – Main notebook with full analysis and modeling
- `submission.csv` – Final submission file (optional)
- `README.md` – This file
---
## 🚀 How to Run
- git clone https://github.com/Nikhilsai-M/titanic-survival-prediction.git
- cd titanic-survival-prediction
- jupyter notebook run