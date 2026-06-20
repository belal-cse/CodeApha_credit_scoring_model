# Credit Scoring Model

## Project Overview

This project aims to build a **Credit Scoring Model** to predict whether a customer is **creditworthy** or **risky** based on financial information such as income, loan amount, interest rate, employment length, and credit history.

The model helps financial institutions in making loan approval decisions.

---

## Dataset

Dataset used: **Credit Risk Dataset**

Features include:

* Person Age
* Person Income
* Home Ownership
* Employment Length
* Loan Intent
* Loan Grade
* Loan Amount
* Loan Interest Rate
* Loan Percent Income
* Previous Default History
* Credit History Length

Target Variable:

* **loan_status**

  * `0` = Safe Customer
  * `1` = Risky Customer

---

## Steps Performed

### 1. Data Loading

Loaded dataset using Pandas.

### 2. Data Cleaning

Handled missing values:

* `person_emp_length`
* `loan_int_rate`

Used median values for filling missing data.

### 3. Data Preprocessing

Converted categorical features into numerical format using One-Hot Encoding.

### 4. Train-Test Split

Split dataset into:

* 80% Training Data
* 20% Testing Data

### 5. Feature Scaling

Applied StandardScaler for better model performance.

### 6. Model Training

Used **Logistic Regression** for classification.

---

## Model Evaluation Metrics

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score

These metrics help measure the performance of the model.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook
* GitHub

---

## Project Structure

CodeApha_credit_scoring_model/
│── credit_scoring_model.ipynb
│── credit_risk_dataset.csv
│── README.md

---

## Conclusion

This project demonstrates how machine learning can be used in financial risk assessment to classify customers based on their creditworthiness.

It is useful for banks and financial institutions to reduce financial risks.
