# 🏠 Boston Housing Price Prediction using Linear Regression

This machine learning project predicts housing prices in Boston using a **Linear Regression** model. It demonstrates fundamental ML practices like EDA, data preprocessing, model training, evaluation, and visualization.

---

## 📌 Overview

- **Objective:** Predict median house prices in Boston suburbs.
- **Model Used:** Linear Regression
- **Dataset:** Boston Housing Dataset (from scikit-learn)
- **Language:** Python
- **Tools & Libraries:** scikit-learn, pandas, matplotlib, seaborn

---

## 🧠 Features Used

- CRIM – Crime rate per capita
- RM – Average number of rooms per dwelling
- TAX – Property-tax rate
- PTRATIO – Pupil-teacher ratio
- LSTAT – % lower status population
- INDUS, NOX, DIS, AGE, etc.

---

## 🛠️ Project Workflow

1. Load dataset from `sklearn.datasets`
2. Exploratory Data Analysis (EDA) using seaborn & matplotlib
3. Feature selection
4. Train-Test split
5. Model training using `LinearRegression()`
6. Evaluation using:
   - R² Score
   - Mean Squared Error (MSE)
7. Save model using `joblib`
8. Predict new data

---

## 📈 Model Performance

| Metric        | Value       |
|---------------|-------------|
| R² Score      | 0.74 (approx) |
| MAE           | ~3.2        |

---

