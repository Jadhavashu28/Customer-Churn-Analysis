1️⃣ Project Title
Customer Churn Analysis using Python
2️⃣ Project Overview
This project analyzes customer churn using Python, Pandas, Matplotlib, and Scikit-Learn.
The goal is to identify key factors influencing churn and build a predictive model.
3️⃣ Dataset Information
The dataset contains customer demographic, service usage, and churn status details.
Features include:
CustomerID – Unique ID of customers
Tenure – Duration customer has stayed with the company
MonthlyCharges – Customer's monthly bill
TotalCharges – Total money spent
Contract Type – Type of contract (Month-to-Month, One year, Two years)
Churn – (Target Variable: Yes/No)
4️⃣ Data Cleaning & Preprocessing
Handled missing values in TotalCharges column.
Converted categorical variables (Contract, PaymentMethod) into numerical form using one-hot encoding.
Scaled numerical features using StandardScaler.
5️⃣ Exploratory Data Analysis (EDA) 📊
Used Matplotlib & Seaborn to analyze churn trends:
Higher churn rate for Month-to-Month contracts.
Customers with higher MonthlyCharges tend to churn more.
6️⃣ Model Building & Evaluation 🤖
Machine Learning Models Used:
✅ Logistic Regression
✅ Random Forest Classifier
✅ XGBoost
Best model: Random Forest with 85% accuracy.
7️⃣ Key Insights & Business Recommendations
Offer discounts or loyalty programs for Month-to-Month users.
Improve customer engagement for users with high MonthlyCharges.
Provide incentives for long-term contracts.
