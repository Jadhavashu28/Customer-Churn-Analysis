# Customer Churn Analysis

# 📌 Project Overview

This project analyzes customer churn behavior using Python. The goal is to identify factors influencing churn and build a predictive model. The analysis includes data cleaning, exploratory data analysis (EDA), and visualization.

# 🛠️ Technologies & Libraries Used
Python
Pandas, NumPy (Data Handling)
Matplotlib, Seaborn (Data Visualization)

# 📊 Dataset Information
Contains customer demographic, service usage, and churn status.

Key Features:
CustomerID: Unique identifier for customers
Tenure: Duration with the company
MonthlyCharges: Monthly bill amount
TotalCharges: Cumulative amount paid
Contract Type: Type of contract (Month-to-Month, One Year, Two Years)
Churn: (Target Variable - Yes/No)

# 🔍 Data Cleaning & Preprocessing
Handled missing values by replacing blanks with 0.
Converted SeniorCitizen values from (0,1) to (Yes, No) for better readability.
Applied feature engineering for contract types and tenure groups.
