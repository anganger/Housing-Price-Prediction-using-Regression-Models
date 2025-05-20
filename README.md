# Housing Price Prediction using Regression Models🏠

This project is part of an assignment for my Machine Learning course at Forman Christian College University. It involves analyzing housing prices using various regression models on a real-world dataset from Taiwan.

## 📁 Dataset

The dataset (`data_1.csv`) contains information about real estate properties, including:
- Transaction date
- House age
- Distance to the nearest MRT station
- Number of convenience stores nearby
- Latitude and Longitude
- House price per unit area (target variable)

---

## 🧠 Objectives

- Explore and visualize the dataset
- Apply and compare multiple regression models:
  - Linear Regression
  - Ridge Regression
  - Lasso Regression
  - ElasticNet Regression
  - Polynomial Regression
- Evaluate models using MSE and R² metrics
- Visualize feature relationships and model coefficients

---

## 🛠️ Technologies Used

- Python 3.x
- pandas, numpy
- seaborn, matplotlib
- scikit-learn

---

## 📊 Key Visualizations

- Histograms and pairplots for data exploration
- Heatmap for feature correlation
- Scatter plots of features vs target variable
- Bar plots showing model coefficients
- Comparison plots of MSE for all models

---

## 🧪 Results

- **Polynomial Regression** performed the best, achieving the lowest MSE.
- **Latitude** showed strong positive correlation with price.
- **Distance to MRT** had a noticeable negative impact on housing price.
- Regularized models (Ridge, Lasso, ElasticNet) helped mitigate overfitting.

---
