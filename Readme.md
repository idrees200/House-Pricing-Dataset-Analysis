# House Pricing Dataset Analysis

## Overview
This project analyzes the House Pricing dataset to predict housing prices using linear regression. It includes preprocessing steps, outlier detection, normalization, and model evaluation.

## Dataset
The dataset (`House Pricing.csv`) provides comprehensive information on housing attributes and prices.

## Project Structure
- **Data Preprocessing**:
  - Missing Values: Handled missing values by replacing them with the mean.
  - Outlier Detection: Detected outliers using the IQR method and replaced them with mean values.
  - Normalization: Normalized selected columns (`tax`, `lstat`) to ensure consistent scaling.

- **Linear Regression Model**:
  - **Feature Selection**: Used `rm` (average number of rooms per dwelling) as the predictor.
  - **Model Training**: Trained a linear regression model to predict `medv` (median value of owner-occupied homes).
  - **Model Evaluation**: Evaluated the model using Mean Squared Error (MSE) and R-squared metrics.

## Results
The model achieved [MSE value] and [R-squared value], indicating [interpretation of model performance].

## Conclusion
This analysis demonstrates the application of linear regression for predicting housing prices based on selected attributes. Further enhancements could involve exploring additional features or trying different regression techniques for improved accuracy.

