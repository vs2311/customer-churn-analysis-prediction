# 📊 Customer Churn Analysis & Prediction

---

⭐ **End-to-End Customer Churn Analysis & Prediction**

**Tools Used:** Python | SQL | Power BI | Scikit-learn | XGBoost

**Focus:** Business Insights, Churn Prediction & Customer Risk Segmentation

---

## 📌 Overview

This project analyzes customer churn in a telecom dataset to identify key factors influencing customer attrition and predict customers who are at higher risk of churning.

The project combines **data analysis, visualization, and machine learning** to generate actionable business insights and support customer retention strategies.

---

## 🎯 Problem Statement

Customer churn is a major challenge for telecom companies.

This project aims to:

- Identify factors influencing customer churn
- Understand customer segments with higher churn rates
- Predict the probability of customer churn
- Identify high-risk customers
- Provide actionable strategies to improve customer retention

---

## 📂 Dataset

The dataset contains telecom customer information with **7,043 records** and multiple attributes related to customer demographics, services, contract details, and billing.

### Key Columns

- Gender
- SeniorCitizen
- Partner
- Dependents
- Tenure
- InternetService
- OnlineSecurity
- OnlineBackup
- TechSupport
- Contract
- PaperlessBilling
- PaymentMethod
- MonthlyCharges
- TotalCharges
- Churn

---

## 📊 Exploratory Data Analysis

The dataset was cleaned and analyzed using **Python, Pandas, and visualization libraries** to understand customer behavior and churn patterns.

Key areas analyzed include:

- Churn distribution
- Churn by contract type
- Churn by internet service
- Churn by payment method
- Churn by gender
- Churn by tenure
- Monthly charges and customer behavior

---

## 📈 Power BI Dashboard

An interactive Power BI dashboard was created to analyze customer churn and identify important business patterns.

### Dashboard Preview

![Dashboard](churn_dashboard.png)

### Key Metrics

- **Total Customers:** 7,043
- **Churned Customers:** 1,869
- **Average Monthly Charges:** 64.76
- **Churn Rate:** 26.54%

---

## 🔍 Key Insights

- Customers with **month-to-month contracts have the highest churn rate**.
- **Fiber optic internet users churn more frequently than DSL users**.
- Customers using **electronic check payment method show higher churn**.
- Customers with **tenure less than 1 year are more likely to churn**.

---

## 🤖 Machine Learning — Churn Prediction

Machine learning models were developed to predict customer churn based on customer demographics, services, contract details, and billing information.

### Data Preprocessing

The following preprocessing steps were performed:

- Removed the `customerID` identifier from model features
- Converted the target variable `Churn` into binary values
- Separated numerical and categorical features
- Applied **One-Hot Encoding** to categorical variables
- Split the data into training and testing sets

---

## 🧠 Models Used

Three classification models were trained and compared:

1. **Logistic Regression**
2. **Random Forest**
3. **XGBoost**

Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

### Model Comparison

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 79.42% | 63.12% | 54.01% | 58.21% | 84.03% |
| Random Forest | 78.64% | 62.05% | 50.27% | 55.54% | 82.05% |
| XGBoost | 80.13% | 66.32% | 51.07% | 57.70% | 84.01% |

---

## 🎚️ Threshold Tuning

Since identifying potential churners is important for customer retention, the classification threshold of the Logistic Regression model was tuned to improve churn detection.

The threshold was changed from **0.50 to 0.45**.

### Final Model Performance

At a **0.45 probability threshold**:

- **Accuracy:** 79.63%
- **Precision:** 61.60%
- **Recall:** 61.76%
- **F1 Score:** 61.68%
- **ROC-AUC:** 84.03%

The adjusted threshold improved recall from **54.01% to 61.76%**, allowing the model to identify more customers who are likely to churn.

---

## ⚠️ Customer Risk Segmentation

Using the final Logistic Regression model, churn probabilities were generated for customers.

Customers were classified into two risk categories:

- **High Risk:** Churn Probability ≥ 0.45
- **Low Risk:** Churn Probability < 0.45

This helps businesses prioritize customers for targeted retention campaigns.

---

## 🚀 Actionable Insights

Based on the analysis and prediction results:

- High-risk customers can be prioritized for retention campaigns.
- Customers with short-term contracts can be targeted with long-term contract offers.
- Customers with high monthly charges can be provided with personalized pricing plans.
- Fiber optic customers can be analyzed further to identify service-related churn drivers.
- Customers with higher predicted churn probability can receive proactive retention offers.

---

## 💡 Business Recommendations

- Offer discounts or incentives for long-term contracts.
- Target high-risk customers with personalized retention campaigns.
- Improve service quality for customers using fiber optic services.
- Provide competitive pricing strategies for high-charge customers.
- Use churn probability scores to prioritize retention efforts.

---

## 🛠️ Tools & Technologies

- **Python** – Data cleaning, preprocessing, EDA and machine learning
- **Pandas & NumPy** – Data manipulation and numerical analysis
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Machine learning and model evaluation
- **XGBoost** – Gradient boosting classification
- **SQL** – Data querying and analysis
- **Power BI** – Interactive dashboard and business visualization

---

## 📁 Project Structure

```text
customer-churn-analysis/
│
├── dataset/
│   └── customer_churn.csv
│
├── python/
│   └── customer_churn_analysis.py
│
├── sql/
│   └── churn_analysis.sql
│
├── powerbi/
│   └── customer_churn_dashboard.pbix
│
├── churn_dashboard.png
│
├── customer_churn_ml_predictions.ipynb
│
└── README.md

---

##🧠 Project Workflow


Raw Data
   ↓
Data Cleaning & Preprocessing
   ↓
Exploratory Data Analysis
   ↓
SQL Analysis
   ↓
Power BI Dashboard
   ↓
Feature Engineering & Encoding
   ↓
Model Training
   ↓
Model Comparison
   ↓
Threshold Tuning
   ↓
Churn Probability Prediction
   ↓
Customer Risk Segmentation
   ↓
Business Recommendations

---

##💼 Why This Project Matters

This project demonstrates an end-to-end approach to solving a real-world customer churn problem using both Data Analytics and Machine Learning.

It covers:

-Data Cleaning
-Exploratory Data Analysis
-SQL Analysis
-Data Visualization
-Business Intelligence
-Machine Learning
-Model Evaluation
-Threshold Optimization
-Churn Probability Prediction
-Customer Risk Segmentation
-Business Decision-Making


---

## 👤Author

**Vijay Saroj**
B.Tech(ECE)
IIT (ISM) Dhanbad

