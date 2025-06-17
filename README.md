# Telecom Customer Churn Analysis

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-lightgrey?logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-orange?logo=plotly)
![Jupyter](https://img.shields.io/badge/Made%20with-Jupyter%20Notebook-orange?logo=jupyter)
![Status](https://img.shields.io/badge/Status-EDA%20Complete%2C%20Modeling%20Pending-yellow)

---

A complete exploratory data analysis (EDA) project focused on customer churn in the telecom industry. This notebook identifies churn risk factors through statistical summaries and visual exploration. Modeling is planned as the next phase.

## 📊 Dataset

The dataset contains customer-level information such as:

- Account duration, usage (day/evening/night/international)
- Service plans (international and voicemail)
- Customer service interactions
- Churn label (True/False)

Source: [Kaggle – Telecom Churn Dataset](https://www.kaggle.com/datasets/mnassrib/telecom-churn-datasets/data)

## 🧪 Analysis Summary

Key steps in the notebook include:

- Data cleaning and formatting (no missing/duplicate values)
- Univariate and bivariate analysis
- Visual comparison of churned vs. retained customers
- Correlation matrix and feature behavior by churn

## ✅ Key Findings

- 📞 Customers with an **international plan** are ~4× more likely to churn.
- ⏱️ **High daytime usage** (minutes/charges) is associated with higher churn.
- ❌ More **customer service calls** often precede churn.
- 🔒 Customers with a **voicemail plan** churn less.
- 🌎 Churn rates vary by **state**, but are more meaningful when weighted by customer count.

## 🚀 Next Steps

- Perform **feature engineering**.
- Train, evaluate, and interpret a **classification model** to predict churn.
- Suggest **retention strategies** for high-risk customers.

## 🛠️ Tools Used

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Jupyter Notebook