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

1. Load dataset from `github/dataprofessor`
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
| MSE           | ~21.6        |

---

📊 Data Visualization
Exploratory Data Analysis (EDA) was done using various plots to understand the features and their relationships with the target variable (MEDV – Median value of owner-occupied homes). Visualizations include:

Heatmap of Correlation Matrix – to identify which features are most correlated with house prices

Pairplots – to observe pairwise relationships between key variables

Histogram/Distribution Plots – to understand the distribution of individual features

Scatter Plots – to visualize the linear relationship between features like RM (average number of rooms) and MEDV

Boxplots – to detect outliers in features like LSTAT, PTRATIO

These visualizations helped guide feature selection and improve model performance.
