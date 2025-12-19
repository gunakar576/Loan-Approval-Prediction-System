#  Loan Approval Prediction System (Machine Learning)

##  Project Overview
The **Loan Approval Prediction System** is a machine learning classification project that predicts whether a loan application will be **Approved** or **Rejected** based on applicant details such as income, credit score, assets, education, and employment status.

This project demonstrates a complete **end-to-end machine learning pipeline**, including data preprocessing, feature engineering, model training, evaluation, and prediction.



---

##  Objective
- Automate the loan approval decision process  
- Reduce human bias and manual effort  
- Improve accuracy and consistency in loan approvals  

---

##  Dataset Description
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

##  Feature Engineering
- Removed unnecessary column (`loan_id`)
- Cleaned column names and string values
- Converted categorical variables into numerical values
- Created a new feature:




- Dropped individual asset columns after aggregation

---

## 🧠 Machine Learning Model
- **Algorithm:** Logistic Regression  
- **Problem Type:** Binary Classification  
- **Why Logistic Regression?**
  - Suitable for binary outcomes
  - Interpretable and efficient
  - Performs well on structured data

---

##  Tech Stack
- **Language:** Python  
- **Libraries:**
  - pandas
  - numpy
  - scikit-learn
  - matplotlib (optional)

---

##  Project Workflow
1. Data loading and exploration  
2. Data cleaning and preprocessing  
3. Feature engineering  
4. Train-test split (80% / 20%)  
5. Feature scaling using StandardScaler  
6. Model training  
7. Model evaluation  
8. Prediction on new data  

---

##  Model Performance
- **Accuracy:** **91.56%**




