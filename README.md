# 🏦 Bank Customer Churn Prediction System

An end-to-end Machine Learning web application designed to predict customer attrition risk for banking institutions. Built with **Python**, **Scikit-Learn**, and **Streamlit**, this tool enables proactive retention strategies by analyzing historical customer demographic and financial behavior.

---

## 📌 Features

* **Real-time Attrition Prediction**: Instantly predicts whether a customer is likely to stay or exit.
* **Interactive Web Dashboard**: Streamlit-powered UI allowing dynamic user input for custom customer profiles.
* **Feature Preprocessing Pipeline**: StandardScaler normalization and one-hot encoding for categorical variables.
* **Machine Learning Engine**: Powered by a trained Random Forest Classification model.

---

## 📊 Dataset Overview

The project uses the **Bank Customer Churn Modeling Dataset** containing historical records of 10,000 customers.

Key features evaluated:
* **Demographics**: Age, Gender, Geography (France, Germany, Spain)
* **Financial Profile**: Credit Score, Account Balance, Estimated Salary
* **Account Activity**: Tenure, Number of Products, Has Credit Card, Active Member Status
* **Target Variable**: `Exited` (1 = Customer Left, 0 = Customer Retained)

---

## 🛠️ Tech Stack & Dependencies

* **Language**: Python 3.9+
* **Machine Learning & Data Processing**: `scikit-learn`, `pandas`, `numpy`
* **Web Framework**: `streamlit`
* **Model Serialization**: `pickle`

---

## 📂 Project Structure

```text
├── Churn_Modelling.csv             # Raw bank churn dataset
├── customer_data.csv               # Extracted features dataset
├── customer_data.xlsx              # Excel formatted customer data
├── churn_analysis.ipynb            # EDA, feature engineering, and model training notebook
├── app.py                          # Streamlit web application interface
├── random_forest_churn_model.pkl   # Serialized trained Random Forest classifier
├── scaler.pkl                      # Serialized StandardScaler object
└── README.md                       # Project documentation
