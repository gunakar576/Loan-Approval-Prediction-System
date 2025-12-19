# 🏦 Loan Approval Prediction System (Machine Learning)

## 📌 Project Overview
The **Loan Approval Prediction System** is a machine learning classification project that predicts whether a loan application will be **Approved** or **Rejected** based on applicant details such as income, credit score, assets, education, and employment status.

This project demonstrates a complete **end-to-end machine learning pipeline**, including data preprocessing, feature engineering, model training, evaluation, and prediction.

> ⚠️ Note: This is a **classification problem**, and hence **Logistic Regression** is used (not Linear Regression).

---

## 🎯 Objective
- Automate the loan approval decision process  
- Reduce human bias and manual effort  
- Improve accuracy and consistency in loan approvals  

---

## 📊 Dataset Description
The dataset contains **4,269 records** with the following features:

| Feature | Description |
|-------|-------------|
| no_of_dependents | Number of dependents |
| education | Graduate (1), Not Graduate (0) |
| self_employed | No (1), Yes (0) |
| income_annum | Annual income |
| loan_amount | Loan amount requested |
| loan_term | Loan tenure |
| cibil_score | Credit score |
| asset | Total assets (engineered feature) |
| loan_status | Target variable (Approved = 1, Rejected = 0) |

---

## ⚙️ Feature Engineering
- Removed unnecessary column (`loan_id`)
- Cleaned column names and string values
- Converted categorical variables into numerical values
- Created a new feature:

