# 🏡 House Price Predictions of California Housing

_Machine Learning • Exploratory Data Analysis • Regression Modeling_

📌 Project Overview

This project analyzes the California Housing dataset to build a predictive model for estimating house prices based on demographic, geographic, and socio-economic features.

Using Python, scikit-learn, statistical analysis, and feature engineering, the project provides:

Cleaned and validated housing data

Insights into relationships between income, population density, proximity, and home values

Predictive models such as Linear Regression, Random Forest, and Gradient Boosting

Model evaluation using MAE, RMSE, R²

A deployable Streamlit application (optional)

🎯 Objectives

✔ Understand factors that influence California housing values
✔ Create an end-to-end ML pipeline
✔ Perform in-depth EDA and data visualization
✔ Build high-accuracy predictive models
✔ Present metrics and insights for decision-making

🧱 Dataset

You can use either:

Option A — scikit-learn built-in dataset

from sklearn.datasets import fetch_california_housing

Option B — CSV Dataset (Kaggle)
Columns typically include:

| Column             | Description                |
| ------------------ | -------------------------- |
| longitude          | Geographic coordinate      |
| latitude           | Geographic coordinate      |
| housing_median_age | Median age of homes        |
| total_rooms        | Total rooms in block       |
| total_bedrooms     | Total bedrooms             |
| population         | Population count           |
| households         | Household count            |
| median_income      | Median neighborhood income |
| median_house_value | Target variable            |
