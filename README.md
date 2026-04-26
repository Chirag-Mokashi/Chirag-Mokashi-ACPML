# Delivery Time Prediction — Linear Regression

A linear regression model to predict product delivery time based on order and logistics features.

## Overview

This project applies simple and multiple linear regression to predict how long a delivery will take given factors such as order size, distance, and shipping method. The analysis includes exploratory data analysis, feature selection, model training, and evaluation.

## Contents

The notebook (`Linear_Regression_Delivery_Time.ipynb`) covers:

1. **EDA** — distribution plots, correlation heatmaps, outlier detection
2. **Feature Engineering** — encoding categorical variables, handling missing values
3. **Model Training** — OLS linear regression with scikit-learn
4. **Evaluation** — MAE, RMSE, R² score, residual plots
5. **Interpretation** — feature coefficients and their business meaning

## Tech Stack

- Python, Pandas, NumPy
- Scikit-learn (LinearRegression)
- Matplotlib, Seaborn

## Setup

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

Open the `.ipynb` notebook file from the zip archive in Jupyter or Google Colab to run the analysis.