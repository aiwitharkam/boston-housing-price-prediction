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

## 📊 Data Visualization

As part of the **Exploratory Data Analysis (EDA)**, various data visualization techniques were used to understand the dataset and gain insights into the relationships between the features and the target variable (**Median Value of Homes** - `MEDV`).

Key visualizations include:

- **Correlation Heatmap:**  
  A heatmap was used to visualize the correlations between the features, helping to identify the strongest relationships with the target variable (`MEDV`). This analysis guided feature selection for the model.

- **Pairplots:**  
  Pairplots were created to show pairwise relationships between key features, providing a better understanding of how each feature correlates with others and how they relate to the house prices.

- **Histograms & Distribution Plots:**  
  These plots were used to examine the distribution of individual features, such as `CRIM`, `RM`, and `LSTAT`, and assess their skewness and the presence of outliers.

- **Scatter Plots:**  
  Scatter plots were used to analyze the linear relationships between the target variable `MEDV` and continuous features like `RM` (average number of rooms per dwelling), which showed a clear positive relationship.

- **Boxplots:**  
  Boxplots were used to identify outliers in features like `LSTAT` (percentage of lower status population) and `PTRATIO` (pupil-teacher ratio), providing insights into potential data issues.

These visualizations were instrumental in understanding the data and making decisions about which features to include in the final model.

---
