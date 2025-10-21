# Housing-California
Machine Learning project for predicting California housing prices. This project applies data preprocessing, feature engineering, and regression models to analyze and predict housing values using the California Housing dataset. Built with scikit-learn, pandas, and matplotli
# 🏡 California Housing Price Prediction — Machine Learning Project

A machine learning project that predicts **California housing prices** using regression models.  
The project demonstrates data preprocessing, feature engineering, model training, and evaluation using the **California Housing dataset**.

---

## 📘 Overview
This project aims to analyze and predict housing prices in California using **Supervised Learning (Regression)** techniques.  
The steps include:
1. Importing and exploring the dataset  
2. Cleaning and preprocessing the data  
3. Feature engineering and scaling  
4. Splitting data into training and testing sets  
5. Training regression models (Linear, Decision Tree, Random Forest, etc.)  
6. Evaluating performance using **RMSE, MAE, and R²**

---

## 🧠 Machine Learning Models Used
- `LinearRegression`
- `DecisionTreeRegressor`
- `RandomForestRegressor`
- `GradientBoostingRegressor`
- `XGBoost` *(optional if used)*

---

## 🧩 Tools & Libraries
`Python`, `pandas`, `numpy`, `matplotlib`, `seaborn`,  
`scikit-learn`, `xgboost` *(optional)*

---

## 📊 Dataset
- **California Housing Dataset** from `sklearn.datasets`
- Features include:
  - Median income
  - House age
  - Average rooms
  - Population
  - Latitude / Longitude  
  - Median house value (target)

---

## 🚀 How to Run
### Option 1 — In Google Colab  
You can open and run the notebook directly in Colab:  
[![Open in Colab]([https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/duaabn/Housing_California/blob/main/Housing_California_Analysis.ipynb](https://colab.research.google.com/drive/1sliSGRz42oRX-SCG6sGZrNZYPFlHB7D2#scrollTo=EgdLA98lPKl9))

### Option 2 — Locally
```bash
pip install -r requirements.txt
jupyter notebook
