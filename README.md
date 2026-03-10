# 🏠 House Price Prediction

A Machine Learning project that predicts house prices based on features such as area, number of bedrooms, bathrooms, and stories.

This project demonstrates an end-to-end workflow in Data Science including data analysis, model training, evaluation, and deployment.

---

## 📌 Project Overview

House prices depend on many factors such as size, location, and amenities.  
This project uses Machine Learning to build a model that predicts the price of a house based on its features.

The goal is to build a predictive model that can estimate house prices accurately using historical housing data.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA)
- Build a predictive machine learning model
- Evaluate model performance
- Create a simple API for predictions
- Demonstrate a full Data Science project workflow

---

## 📂 Dataset

Dataset: `house_prices.csv`

Features used in the dataset:

| Feature | Description |
|------|------|
| area | Size of the house (square feet) |
| bedrooms | Number of bedrooms |
| bathrooms | Number of bathrooms |
| stories | Number of floors |
| price | House price (target variable) |

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Flask

These tools are commonly used in Machine Learning and Data Science projects.

---

## 🔍 Exploratory Data Analysis

Key analysis steps performed:

- Data inspection
- Missing value analysis
- Correlation analysis
- Feature visualization
- Price distribution analysis

Example visualizations:

- Correlation heatmap
- Area vs Price scatter plot
- Price distribution histogram

---

## 🤖 Machine Learning Model

Model Used:

- Linear Regression

Steps involved:

1. Data preprocessing
2. Feature selection
3. Train-test split
4. Model training
5. Model evaluation

---

## 📊 Model Evaluation

Evaluation metrics used:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics help measure how accurate the model predictions are.

---

## 🚀 Model Deployment

A simple prediction API was created using Flask.

The API takes house features as input and returns the predicted price.

Example API request:
