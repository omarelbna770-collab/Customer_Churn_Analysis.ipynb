# 📉 Telco Customer Churn Analysis

## 📌 Project Overview
An Exploratory Data Analysis (EDA) and data cleaning project on the Telco Customer Churn dataset to identify key drivers behind customer churn and pinpoint high-risk segments.

## 🛠️ Tech Stack & Tools
- **Languages:** Python
- **Libraries:** Pandas, NumPy, Seaborn, Matplotlib
- **Environment:** Google Colab / Kagglehub

## 🔍 Key Data Cleaning & Preprocessing Steps
1. **Handling Missing Values:** Standardized hidden whitespace values in `TotalCharges` and converted the feature to numerical type (`float`).
2. **Data Standardization:** Grouped and converted binary features (`Yes`/`No`, `Gender`) into standard numerical labels (`1`/`0`).
3. **One-Hot Encoding:** Encoded multi-class categorical features like `Contract` type and `PaymentMethod`.

## 📊 Key Business Insights
- **High Risk Period:** Customers are most vulnerable to churning within their **first 12 months** (Churn rate ~ 48%).
- **Senior Citizens:** Senior citizens experience a significantly higher churn rate compared to non-senior customers (> 40%).
- **Customer Lifetime Value:** Long-term customers (Tenure > 48 months) show strong loyalty with minimal churn rates (< 10%).
