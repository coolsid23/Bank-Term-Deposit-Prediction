# Bank-Term-Deposit-Prediction

Bank marketing campaign analysis and term deposit prediction using machine learning.

## Project Overview

This project analyzes a bank marketing dataset and builds machine learning models to predict whether a customer will subscribe to a term deposit.

The objective is to help financial institutions identify potential customers and improve the effectiveness of marketing campaigns.

---

## Problem Statement

Banks conduct marketing campaigns to encourage customers to subscribe to term deposits. However, contacting every customer is costly and inefficient.

The goal of this project is to develop a predictive model that identifies customers who are more likely to subscribe, allowing banks to target their marketing efforts effectively.

---

## Dataset

Dataset: Bank Marketing Dataset

Features include:

* Age
* Job
* Marital Status
* Education
* Balance
* Housing Loan
* Personal Loan
* Contact Type
* Month
* Duration
* Campaign Information
* Previous Campaign Outcomes

Target Variable:

* y (Yes/No subscription to term deposit)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Project Workflow

### 1. Data Inspection

* Dataset loading
* Data type checking
* Missing value analysis
* Duplicate detection

### 2. Exploratory Data Analysis (EDA)

* Customer demographics analysis
* Subscription distribution
* Correlation analysis
* Feature visualization

### 3. Data Preprocessing

* Handling categorical variables
* Feature encoding
* Train-Test Split
* Feature scaling

### 4. Model Building

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

### 5. Model Evaluation

* Accuracy Score
* Precision
* Recall
* F1 Score
* ROC-AUC Score

---

## Key Findings

* Call duration strongly influences subscription decisions.
* Previous campaign outcomes significantly affect customer responses.
* Marketing campaigns performed better during specific months.
* Random Forest achieved the best overall performance among the tested models.

---

## Results

| Model               | Performance      |
| ------------------- | ---------------- |
| Logistic Regression | Good Baseline    |
| Decision Tree       | Moderate         |
| Random Forest       | Best Performance |

---

## Future Improvements

* Hyperparameter tuning
* Cross-validation
* XGBoost implementation
* Deployment using Flask/FastAPI
* Interactive dashboard development


