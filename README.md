# 🏡 Property Price Prediction – Capstone Project

<p align="center">
  <img src="https://img.shields.io/badge/pandas-Used-0A74DA?logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/numpy-Used-4D77CF?logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/matplotlib-Used-007ACC?logo=matplotlib&logoColor=white" />
  <img src="https://img.shields.io/badge/seaborn-Used-2D3E50?logo=seaborn&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-Used-F7931E?logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/xgboost-Used-FF6600?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/joblib-Used-13AA52?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/warnings-Used-B0B0B0" />
  <img src="https://img.shields.io/badge/math-Used-8E8E8E" />
</p>

Welcome to my **Property Price Prediction** capstone project! 🎓  
This project aims to predict property prices using Machine Learning based on various housing-related features. It's a complete end-to-end regression pipeline created as part of my Data Science training journey. 🚀

## 🎯 Goal

To accurately predict the **property price** based on multiple input features like area, location, number of bedrooms, and more, using the best-performing ML model.

---

## 📂 Project Overview

This notebook walks through an end-to-end supervised learning workflow on structured housing data. It includes:

- 📥 Data Loading  
- 🧹 Data Cleaning & Preprocessing  
- 📊 Exploratory Data Analysis (EDA)  
- 🧠 Feature Engineering  
- 🤖 Model Building (Linear, Tree-based, Ensemble)  
- 🧪 Model Evaluation  
- 💾 Model Saving

---

## 🧠 Problem Statement

The goal is to **predict the `PropPrice` (property price)** using various features such as zone, frontage, area, amenities, quality, and more.

This prediction model can help:

- 🏘️ Home buyers/sellers to estimate fair prices  
- 🏢 Real estate platforms to enhance their listings  
- 📈 Analysts to understand pricing patterns

---

## 📊 Dataset

The dataset (`Property_data.csv`) was already provided.  
It contains features like:

- **Categorical**: `PropertyZone`, `Street`, `Alley`, `Amenities`, etc.  
- **Numerical**: `PropertySize`, `GarageArea`, `YearBuilt`, etc.  
- **Target Variable**: `PropPrice` (Property Price)

---

## 📦 Libraries & Modules Used

<p align="center">
  <img src="https://img.shields.io/badge/pandas-Used-blue?logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/numpy-Used-blue?logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/matplotlib-Used-blue?logo=matplotlib&logoColor=white" />
  <img src="https://img.shields.io/badge/seaborn-Used-blue?logo=seaborn&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-Used-blue?logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/xgboost-Used-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/joblib-Used-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/warnings-Used-lightgrey" />
  <img src="https://img.shields.io/badge/math-Used-lightgrey" />
</p>

---

## 🛠️ Workflow Overview

1. **🧹 Data Preprocessing -> Data Cleaning & Exploration**

- Cleaned missing values (e.g., `Alley`, `PoolQC`, `BoundaryFeatures`)
- Handled outliers, and explored the dataset through visualizations 📊
- Label encoding & ordinal encoding where needed
- One-hot encoding for nominal categorical variables
- Feature scaling using `StandardScaler`
- Feature selection using PCA (Principal Component Analysis)


2. **📊 Exploratory Data Analysis**

Used various visualizations to explore:

- Distribution of target variable (`PropPrice`)
- Correlation heatmaps 🔥
- Boxplots & scatterplots for key predictors
- Property zones & street types impact on pricing

3. **Feature Engineering**  
   - Extracted number of rooms from `size`
   - Converted `total_sqft` to numeric using logic
   - Applied one-hot encoding to categorical variables

4. **Model Training & Evaluation**  
   - Trained and compared 4 regression models
   - Evaluated using R² Score
   - XGBoost gave the best performance ✅

5. **Model Exporting**  
   - Saved trained model using `joblib` for future deployment

---

## 📂 File Structure

📁 Capstone_Project_Property-Price-Prediction.ipynb ← Main Jupyter notebook

---

## 🤖 Models Applied

The following models were implemented and compared:

- 📏 Linear Regression  
- 🌲 Decision Tree Regressor  
- 🌲 Random Forest Regressor  
- ⚡ XGBoost Regressor  
- 📉 Ridge & Lasso Regression  
- 🔍 GridSearchCV for hyperparameter tuning  
- 📊 PCA for dimensionality reduction

### ✅ Evaluation Metrics

- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  
- R² Score

---

## 🧪 Results & Insights

- Best model: **[Insert best-performing model from notebook]**
- R² Score: **[Insert actual R² score from notebook]**
- Top features influencing price: **[e.g., GrLivArea, YearBuilt, GarageArea, etc.]**

---

## 💾 Model Saving

The final model was saved using `joblib` for future use and deployment.

---

## 🙋‍♂️ About Me

Hi, I’m **Debasis Baidya** from Kolkata 👋  
With 11+ years of experience in the MIS domain, I am now transitioning into the world of **Data Science**.

📫 Feel free to connect:

- 🌐 [LinkedIn](#)
- 💻 [GitHub](#)
- 🔗 [Portfolio / Streamlit App](#)

---

## 🚀 Future Improvements

- Streamlit-based web app for interactive predictions  
- Add geolocation-based insights  
- Hyperparameter optimization with advanced tuning  
- Use CatBoost or LightGBM for performance boosting

---
