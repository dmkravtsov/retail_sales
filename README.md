# Retail Sales Analysis and Revenue Prediction Project

## Overview

This project encompasses a comprehensive analysis of retail sales data and the application of machine learning techniques for revenue prediction. The dataset covers sales, pricing, discounts, and promotional data from March 1, 2022, to June 27, 2023. The primary goals are to identify trends, correlations, and optimize promotional strategies for maximizing revenue.

## Analysis Overview

### Sales Trends and Correlations
- Examination of sales trends, seasonality, and weekly fluctuations.
- Correlation analysis of various features like discount percentage, promotional activities, and product categories.

### Preliminary Data Insights
- Analysis of product types, sales distribution, pricing strategies, and promotional impacts.

## Machine Learning Model

### Revenue Prediction
- Application of the LightGBM model for predicting sales revenue based on historical data.
- Feature engineering to incorporate product details, store specifics, and promotional information.

### Class Imbalance Handling
- Implementation of strategies like weighted loss function and resampling to address class imbalance in the 'has_promo' feature.

### Model Evaluation
- Use of Mean Squared Error (MSE) and R^2 metrics for model performance evaluation.

## Optimization of Product Discounts

### Methodology
- Testing predefined discount levels for each product.
- Revenue prediction for each discount level using the trained model.
- Selection of the optimal discount level to maximize revenue.

### Output
- Generation of a `discount_df` dataset, detailing optimal discount levels for each product.


## Requirements

- Python 3.x
- LightGBM
- Pandas
- NumPy
- Scikit-learn