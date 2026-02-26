# 💻 Laptop Price Prediction - Machine Learning Project

## 📌 Project Overview

This project focuses on analyzing laptop specifications and building a machine learning model to predict laptop prices based on their features.

The project includes:
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Building
- Model Evaluation
- Model Comparison

---

## 🎯 Problem Statement

To build a regression model that can accurately predict the price of laptops using their specifications such as:

- Company
- RAM
- Storage
- CPU Frequency
- GPU
- Screen Resolution
- Operating System
- Weight
- And more...

---

## 📊 Dataset Information

- Total Rows: 1275
- Total Columns: 23
- Target Variable: `Price_euros`

The dataset includes detailed laptop specifications including:

- Hardware details
- Storage types
- Display specifications
- Processor details

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 📈 Exploratory Data Analysis

Performed:

- Company distribution analysis
- RAM distribution
- Storage type analysis
- OS comparison
- Price distribution
- Correlation heatmap
- Price vs CPU frequency analysis
- Price vs RAM analysis

---

## 🔧 Feature Engineering

- One-Hot Encoding for categorical variables
- Automatic detection of object columns
- Storage feature extraction
- Data cleaning and preprocessing
- Train-Test Split (80-20)

---

## 🤖 Models Implemented

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor
- Stacking Regressor (Advanced)

---

## 📊 Model Evaluation Metrics

- R² Score
- Mean Absolute Error (MAE)

---

## 🏆 Best Performing Model

> Stacking Regressor achieved the best performance with:
> - R² Score: 0.8807
> - MAE:  174.007
<img width="934" height="721" alt="image" src="https://github.com/user-attachments/assets/82d60eb7-d86d-43b9-b5b0-25e6f4deeb61" />

🎯 What This Graph Shows

Each dot = 1 laptop

X-axis = Actual price

Y-axis = Predicted price

Red line = Perfect prediction line

Dots are close to red line → model is good ✅

The model shows good alignment between actual and predicted values indicating strong predictive performance
---

## 📷 Sample Visualization

<img width="524" height="400" alt="Screenshot 2026-02-26 143112" src="https://github.com/user-attachments/assets/b86717b5-db26-47d2-adf2-8b8b93d7b203" />



