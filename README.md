<!-- YES BANK LOGO -->
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/75/Yes_Bank_logo.svg/2560px-Yes_Bank_logo.svg.png" alt="Yes Bank" width="300"/>
</p>

# 📈 Yes Bank Stock Closing Price Prediction | Machine Learning Project

---

## 🧠 Project Overview  
This project focuses on predicting the **closing price** of Yes Bank's stock using historical data and regression-based machine learning models. It demonstrates a full workflow of data preprocessing, exploratory data analysis, feature transformation, model building, and evaluation using Python.

---

## 📁 Dataset Summary  
- **Source:** Historical Yes Bank stock data  
- **Period:** Monthly (2005–2020)  
- **Records:** 185 rows  
- **Target Variable:** `Close` price  
- **Features:** `Open`, `High`, `Low`, `Date`

---

## 🛠 Tools & Libraries Used  

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="40" />
  <img src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width="40" />
  <img src="https://matplotlib.org/_static/images/logo2.svg" width="40" />
</p>

- **Pandas**, **NumPy** – Data cleaning and manipulation  
- **Scikit-learn** – Model training and evaluation  
- **PowerTransformer** – Feature transformation  
- **Matplotlib**, **Seaborn** – Data visualization  
- **mplfinance** – Financial chart formatting  
- **GridSearchCV** – Hyperparameter tuning

---

## 🔄 Workflow Summary

### 1. Data Preprocessing  
- Converted date column to datetime  
- Checked for missing/null values (none found)  
- Applied feature scaling & Power Transformation  
- Split into 80% training and 20% testing set  

### 2. Model Building & Evaluation  
Trained multiple regression models including:
- Linear Regression  
- KNN Regressor  
- Ridge & Lasso Regression  
- Random Forest Regressor  
- ElasticNet

> ✅ **Ridge Regression** delivered the best result with an **R² score of 0.993**

---

## 📌 Key Learnings  
- Feature transformation reduced multicollinearity  
- Ridge Regression performed best due to regularization  
- Multiple models tested with consistent cross-validation  
- Learned how to handle financial data in real-world ML scenarios

---


