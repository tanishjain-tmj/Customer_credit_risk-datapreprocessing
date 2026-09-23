# Customer Credit Risk Data Preprocessing

## 📌 Project Overview

This project focuses on **data preprocessing and feature engineering** for a Customer Credit Risk dataset.

The main objective is to transform raw, inconsistent data into a clean and analysis-ready dataset by applying various preprocessing, outlier handling, feature engineering, encoding, scaling, and transformation techniques.

---

## 📊 Dataset

The dataset contains customer and financial information such as:

- Customer ID
- Age
- Gender
- Region
- Education Level
- Employment Type
- Annual Income
- Loan Amount
- Loan Purpose
- Credit Score
- Repayment History
- Transaction Count
- Economic Index
- Default Flag
- Join Date

Data was acquired from multiple sources including **CSV, JSON, SQL, and API-based data** and combined using `customer_id`.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- SciPy
- Matplotlib
- Jupyter Notebook / Google Colab

---

## 🔄 Data Preprocessing

The project covers the following preprocessing techniques:

### Data Acquisition
- CSV data
- JSON data
- SQL data
- API data
- Data merging using a common customer ID

### Data Exploration
- `info()`
- `describe()`
- Data profiling
- Missing value analysis

### Missing Value Handling
- Simple Imputation
- Most Frequent Imputation
- Random Sample Imputation
- Missing Indicators
- KNN Imputation
- MICE
- Complete Case Analysis

### Outlier Handling
- Z-Score Method
- IQR Method
- Percentile Method
- Winsorization

### Feature Engineering
- Date & time feature extraction
- Year
- Month
- Day
- Weekday
- Binning
- Quantile Binning
- K-Means Binning

### Categorical Encoding
- Ordinal Encoding
- Label Encoding
- One-Hot Encoding

### Feature Scaling
- Standardization (Z-Score)
- Normalization
- Min-Max Scaling
- MaxAbs Scaling
- Robust Scaling

### Feature Transformation
- Log Transformation
- Reciprocal Transformation
- Square Root Transformation
- Box-Cox Transformation
- Yeo-Johnson Transformation
- Column Transformer

### New Feature Construction
- Debt-to-Income Ratio
- Average Monthly Transactions
- Spending-to-Income Ratio

---

## 🎯 Project Objective

The goal of this project is to demonstrate how raw customer credit data can be systematically transformed into **clean, structured, and machine-learning-ready data**.

---

## 📁 Project Structure

```text
Customer-Credit-Risk-Data-Preprocessing/
│
├── data/
│   ├── loan_data.csv
│   ├── customer_metadata.json
│   ├── repayment_history.sql
│   └── economic_indicators_api.json
│
├── Customer_Credit_Risk_Preprocessing.ipynb
│
└── README.md
