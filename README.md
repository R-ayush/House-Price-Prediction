# 🏡 House Price Prediction using Machine Learning

This project predicts house prices using the California Housing Dataset and machine learning techniques, specifically the XGBoost Regressor. The goal is to provide accurate, data-driven price predictions based on housing features such as average income, number of rooms, location, and more.

---

## 📌 Problem Statement

Predicting house prices is a critical task in the real estate industry. Traditional valuation methods are often subjective and inconsistent. This project uses a machine learning approach to develop a predictive model that can estimate house prices based on real-world features.

---

## 🚀 Proposed Solution

We propose a regression-based machine learning solution that:

- Uses the **California Housing Dataset**
- Applies **XGBoost Regressor** for price prediction
- Evaluates performance using **R² Score**, **MAE**, and **RMSE**
- Visualizes correlations and prediction accuracy with graphs

---

## 🛠️ Technologies & Libraries Used

- **Python 3.x**
- **Jupyter Notebook / VS Code**
- Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `xgboost`

---

## 📂 Project Structure

house-price-prediction/
│
├── dataset/ # California housing dataset (loaded from sklearn)
├── visuals/ # Plots and graphs
├── house_price_prediction.ipynb # Main Jupyter notebook
├── README.md # Project description
└── requirements.txt # Library dependencies (optional)


---

## 📈 Model Overview

- **Model Used:** `XGBRegressor`
- **Input Features:**  
  Median income, average rooms, population, housing age, proximity to ocean, etc.
- **Target Variable:**  
  Median house value
- **Performance Metrics:**
  - R² Score
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)

---

## ✅ Results

- Achieved **high accuracy** with R² Score > 0.80 on test data
- Model performs well on both training and unseen data
- Visualizations confirm a strong correlation between actual and predicted prices

