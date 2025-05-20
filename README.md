# 🏠 Housing Price Prediction using Regression Models

This is a Machine Learning course project focused on predicting house prices using various regression techniques on a real-world dataset from Taiwan.

## 📂 Dataset

The dataset includes:
- Transaction date
- House age
- Distance to the nearest MRT station
- Number of nearby convenience stores
- Geographic coordinates (latitude and longitude)
- Price per unit area (target)

> Dataset file: `data_1.csv`

---

## 🧠 Objectives

- Explore and understand the housing price dataset
- Visualize key features and correlations
- Apply and compare multiple regression models:
  - Linear Regression
  - Ridge Regression
  - Lasso Regression
  - ElasticNet Regression
  - Polynomial Regression
- Evaluate model performance using MSE and R²
- Visualize and interpret regression coefficients

---

## ⚙️ Technologies Used

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

---

## 📊 Key Visualizations

- Histograms & pairplots for EDA  
- Heatmap for feature correlation  
- Regression coefficient bar charts  
- Model comparison using MSE bar plots  
- Scatter plots for selected features

---

## 🧪 Results

| Model            | MSE     | R² Score |
|------------------|---------|----------|
| Linear Regression | ~54     | ~0.65     |
| Ridge Regression  | ~55     | ~0.64     |
| Lasso Regression  | ~57     | ~0.63     |
| ElasticNet        | ~56     | ~0.63     |
| Polynomial        | **~43** | **~0.73** |

Polynomial Regression outperformed all others in terms of both Mean Squared Error and R².

---

## 📌 Author

**Abdullah Naeem**  
Machine Learning Student – Forman Christian College University  
GitHub: [@anganger](https://github.com/anganger)

