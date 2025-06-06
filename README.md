# 🔄 Salary Prediction Model using ANN

A deep learning project to predict estimated salary of customers using **Artificial Neural Networks (ANN)**, implemented with **TensorFlow** and **Keras**.

---

## 📊 Problem Statement

- **Dataset**: `Churn_Modelling.csv`
- **Task**: Regression
- **Objective**:  
  Predict the esimated salary of coustomers based on their profile data like:
 - CreditScore
 - Geography
 - Gender
 - Age
 - Tenure
 - Balance
 - NumOfProducts
- etc.

---

## 🛠 Project Pipeline

```mermaid
graph LR
A[Churn Dataset] --> B[Basic Feature Engineering]
B --> C[Convert Categorical to Numerical + Standardization]
C --> D[Create ANN using Keras & TensorFlow]
D --> E[Save Model as Pickle/h5]
E --> F[Prediction-Estimated Salary]
F --> G[Hyper-Parameter-Tuning : GridSearchCV]
