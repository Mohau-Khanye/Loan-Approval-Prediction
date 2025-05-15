# 🧾 Loan Approval Prediction

This project builds a machine learning model to predict whether a loan applicant poses a credit risk. It's designed to help financial institutions make informed, data-driven loan approval decisions.

---

## 🎯 Objective

Predict whether an applicant will default on a loan (Risk_Flag: 1) or not (Risk_Flag: 0), using demographic and professional features.

---

## 🧠 Problem Statement

Financial institutions face significant risk when loans are granted to high-risk applicants. By using historical loan applicant data, we can train supervised classification models to assist in risk assessment and reduce default rates.

---

## 📊 Dataset

The dataset used for this project was sourced from Kaggle: [Loan Approval Prediction Dataset](https://www.kaggle.com/datasets/itssuru/loan-prediction)

- **Features:** 13 columns including:
  - Age
  - Income
  - Profession
  - House Ownership
  - Marital Status
  - Current Job Years
  - Number of Dependents
- **Target Variable:** `Risk_Flag`

---

## ⚙️ Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn)
- Models: Logistic Regression, Decision Tree, Random Forest, Naive Bayes, SVM
- Visualization: Matplotlib, Seaborn

---

## 📈 Project Workflow

1. Data Cleaning & Encoding
2. Exploratory Data Analysis (EDA)
3. Feature Scaling (StandardScaler)
4. Model Training & Evaluation
5. Performance Metrics: Accuracy, F1 Score

---

## 🏆 Best Model Performance

**Random Forest Classifier**  
- Accuracy: **85%**  
- F1 Score (Weighted): **0.83**

---

## 🚀 Future Improvements

- Hyperparameter tuning (GridSearchCV)
- Cross-validation (Stratified KFold)
- Streamlit dashboard deployment


