# Customer Lifetime Value Prediction

This project focuses on predicting the future value a customer brings to a business over the course of their relationship. Using historical transaction data from the Online Retail II dataset, we apply feature engineering, RFM analysis, clustering, and regression modeling to estimate customer lifetime value (CLV).

## 📂 Dataset

- Source: [Online Retail II - UCI](https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset)
- File: `online_retail_II.xlsx`
- Description: UK-based online retail transactions from 2009 to 2011.

## 🎯 Objective

To build a predictive model for Customer Lifetime Value (CLV) using behavioral metrics such as recency, frequency, monetary value, and other derived features to estimate the potential future worth of each customer.

## 🧪 Steps Involved

1. Data Cleaning and Preparation
2. Exploratory Data Analysis (EDA)
3. Feature Engineering (RFM and derived features)
4. Customer Segmentation (optional - KMeans clustering)
5. CLV Prediction Modeling (Regression)
6. Evaluation and Interpretation of Model Results

## 🛠️ Models Used

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor

## 📊 Evaluation Metrics

- R² Score
- RMSE (Root Mean Squared Error)

## 📌 Key Features Used

- Recency, Frequency, Monetary
- Average Order Value
- Purchase Frequency
- Estimated Customer Value
- CLV (estimated as target)

## 📁 Files

- `Project.ipynb` – Jupyter notebook with all code and analysis

## 🧠 Business Insight

The CLV estimates allow businesses to:

- Prioritize marketing efforts on high-value customers
- Design retention strategies for at-risk customers
- Understand behavioral segments of their customer base
