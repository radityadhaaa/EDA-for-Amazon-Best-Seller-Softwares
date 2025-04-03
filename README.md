# EDA for Amazon Best Seller Softwares

## Overview
This repository contains an exploratory data analysis (EDA) of the Amazon best-selling software products. Using the dataset best_sellers_data2.csv, this analysis aims to uncover insights regarding product performance based on ratings, prices, and other relevant features. Multiple machine learning models are implemented to predict product star ratings and enhance understanding of market trends.

## Contents
- **best_sellers_data2.csv**: The dataset containing information on various software products sold on Amazon, including titles, prices, star ratings, the number of ratings, and rankings in different countries.
- **analysis_notebook.ipynb**: Jupyter notebook containing the entire analysis, including data cleaning, exploratory data analysis, model training, and evaluation.

## Key Features of the Analysis
1. Data Loading and Cleaning
The dataset is loaded, cleaned, and preprocessed for analysis, including handling missing values and converting categorical variables to numerical formats.
2. Exploratory Data Analysis:
- Distribution analysis of product star ratings and prices.
- Identification of top-selling products based on average star ratings across different countries.
- Calculation of average prices and trend visualization for software products.
3. Modeling Approaches:
- Implementation of various regression models, including XGBoost, LightGBM, Random Forest, Gradient Boosting, CatBoost, ElasticNet, and Support Vector Regression (SVR).
- Hyperparameter tuning using GridSearchCV to optimize model performance.
- Evaluation of different models using metrics such as Mean Absolute Error (MAE) and R-squared.
4. Ensemble Learning
A stacking regressor is built combining different models to improve prediction accuracy.

## Conclusions
- **Top Performers**: Certain products like Norton 360 and Microsoft Office consistently rank highly in customer ratings.
- **Importance of Ratings**: Higher ratings significantly correlate with better product rankings, indicating that quality assurance plays a vital role in sales.
- **Price Insights**: Competitive pricing impacts sales, evident from the analysis of average prices across different countries.
- **Model Performance**: XGBoost and LightGBM emerge as strong models for predicting ratings, showcasing their robustness in varied datasets.
- **Future Work**: Expanding the dataset with customer demographics or seasonal data may provide deeper insights into purchasing behavior and enhance predictive models.
