# Groundnut_yield_prediction

## Project Overview
Groundnut Yield Prediction is a machine learning-based project aimed at predicting the yield of groundnuts based on various environmental and agricultural factors. The goal is to help farmers and agricultural stakeholders make informed decisions to optimize production and resource allocation.

## Dataset
The dataset used for this project includes features such as:
- Temperature
- Rainfall
- Soil Type
- Fertilizer Usage
- Humidity
- Other relevant agricultural parameters

## Problem Statement
The objective is to develop a predictive model that can accurately estimate the yield of groundnuts based on given input features. This can help in:
- Efficient resource allocation.
- Yield optimization based on climate and soil conditions.
- Better decision-making for farmers and agricultural researchers.

## Approach
1. **Data Preprocessing:**
   - Handling missing values.
   - Encoding categorical variables.
   - Feature scaling and transformation.

2. **Exploratory Data Analysis (EDA):**
   - Identifying patterns and correlations between different features.
   - Visualizing the impact of environmental factors on yield.

3. **Model Selection:**
   - Training various models such as Linear Regression, Random Forest, XGBoost, and other supervised learning techniques.
   - Hyperparameter tuning for improved performance.

4. **Evaluation Metrics:**
   - Mean Squared Error (MSE), R-Squared, and Mean Absolute Error (MAE) to assess model performance.

## Requirements
To run this project, install the following dependencies:
```
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
```
## Results
The best-performing model, Support Vector Regressor (SVR), achieved an R-Squared score of 0.9556, indicating that it explains approximately 95.56% of the variance in groundnut yield based on the given features..

## Future Improvements
- Incorporating real-time weather data for dynamic yield predictions.
- Expanding the dataset with additional agricultural parameters.
- Deploying the model as a web-based application for easy access by farmers.
