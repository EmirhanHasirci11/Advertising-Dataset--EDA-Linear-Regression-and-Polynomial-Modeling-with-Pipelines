# 📊 Advertising - EDA, Linear Regression & Polynomial Regression

This project performs an end-to-end analysis on the classic **Advertising dataset**, which contains data about TV, Radio, and Newspaper advertising budgets and their impact on **Sales**.



The notebook covers:
- Exploratory Data Analysis (EDA)
- Linear Regression
- Polynomial Regression using Scikit-learn Pipelines
- Visualization of model performance

---

## 📓 View the Notebook on Kaggle

You can explore the full interactive notebook on Kaggle here:

👉 [Advertising-Dataset--EDA-Linear-Regression-and-Polynomial-Modeling-with-Pipelines](https://www.kaggle.com/code/emirhanhasrc/advertising-dataset-eda-linear-regression-and-po)

> This version includes all visualizations and analysis directly runnable in a Kaggle environment with the dataset already integrated.

---

## 🧠 Objective

To understand the relationship between advertising budgets and product sales using regression models. We'll explore:
- Which advertising channel influences sales the most?
- Does adding polynomial features improve the prediction accuracy?
- Visual interpretation of regression lines and R² scores for different model degrees.

---

## 🗂️ Dataset Overview

The dataset contains 200 rows and the following columns:

| Column      | Description                                |
|-------------|--------------------------------------------|
| `TV`        | Budget spent on TV ads                     |
| `Radio`     | Budget spent on Radio ads                  |
| `Newspaper` | Budget spent on Newspaper ads              |
| `Sales`     | Units sold (target variable)               |

**Source**: [Advertising-Dataset](https://www.kaggle.com/datasets/ashydv/advertising-dataset/data)

---

## 📌 Key Sections

### 📈 1. Exploratory Data Analysis (EDA)
- Correlation matrix between features and Sales
- Distribution plots for each numerical feature
- Boxplots to detect outliers

### 📉 2. Linear Regression
- Fit a basic Linear Regression model
- Evaluate using R², MAE, and MSE metrics
- Scatter plot to visualize predicted vs actual Sales

### 🔁 3. Polynomial Regression
- Compare polynomial degrees from 1 to 9
- Use `Pipeline` to scale, transform, and fit in one step
- Subplots with prediction curves and R² scores
- Visual differentiation between training and test data
