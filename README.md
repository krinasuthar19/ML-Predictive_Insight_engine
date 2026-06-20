# Predictive Insight Engine: House Price Prediction using Supervised Learning

## Project Overview

Predictive Insight Engine is a supervised machine learning project developed to understand, implement, analyze, and evaluate different regression algorithms for house price prediction.

The project uses a real estate dataset to predict house prices based on various property features such as area, bedrooms, bathrooms, location score, and property age.

The project also explores model evaluation techniques, gradient descent optimization, and bias-variance analysis.

---

## Objective

The objective of this project is to:

* Understand supervised learning algorithms
* Implement regression models for house price prediction
* Evaluate model performance using different metrics
* Understand overfitting and underfitting
* Analyze bias-variance trade-off
* Compare multiple machine learning approaches

---

## Dataset Features

The dataset contains the following features:

* House Area (sq.ft)
* Number of Bedrooms
* Number of Bathrooms
* Location Score
* Age of Property
* Distance from City
* Lot Size
* Garage Availability
* Pool Availability
* Renovation Years Ago
* House Price (Target Variable)

Target Variable:

* `house_price_inr`

---

## Project Structure

### Part A: Conceptual Understanding

Topics covered:

* Supervised Learning
* Regression vs Classification
* Simple Linear Regression
* Linear Regression Assumptions
* Bias-Variance Trade-Off
* Overfitting and Underfitting

### Part B: Dataset Understanding and Preparation

Tasks performed:

* Identify independent and dependent variables
* Visualize relationships between features and target variable
* Split the dataset into training and testing sets

### Part C: Simple Linear Regression

Tasks performed:

* Implement Simple Linear Regression
* Plot regression line
* Validate regression assumptions

### Part D: Model Evaluation Metrics

Metrics used:

* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score
* Adjusted R² Score

### Part E: Multiple Linear Regression

Tasks performed:

* Implement Multiple Linear Regression
* Compare with Simple Linear Regression
* Analyze performance improvements

### Part F: Polynomial Regression

Tasks performed:

* Implement Polynomial Regression
* Compare with Linear Regression
* Identify overfitting and underfitting

### Part G: Gradient Descent Optimization

Methods implemented:

* Batch Gradient Descent
* Stochastic Gradient Descent (SGD)
* Mini-Batch Gradient Descent

### Part H: Bias-Variance and Model Diagnostics

Tasks performed:

* Analyze bias and variance
* Study model complexity
* Identify the best balanced model

### Part I: Final Analysis and Reporting

Topics covered:

* Best performing model
* Impact of gradient descent
* Overfitting and underfitting analysis
* Business interpretation of results

---

## Technologies Used

Programming Language:

* Python

Libraries:

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

Environment:

* Jupyter Notebook

---

## Models Implemented

1. Simple Linear Regression
2. Multiple Linear Regression
3. Polynomial Regression

---

## Evaluation Metrics

The following metrics were used to evaluate model performance:

* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score
* Adjusted R² Score

---

## Key Findings

* Multiple Linear Regression provided the best overall performance.
* Simple Linear Regression showed signs of underfitting because it used only one feature.
* Polynomial Regression may overfit if the degree is too high.
* Mini-Batch Gradient Descent provided a balance between speed and stability.
* Features such as area, location, bedrooms, and bathrooms significantly influence house prices.

---

## Business Application

This project can help real estate companies:

* Estimate house prices accurately
* Analyze important factors affecting house prices
* Support data-driven pricing decisions
* Improve business forecasting

---

## Conclusion

This project successfully demonstrated the implementation and evaluation of supervised learning techniques for house price prediction.

Different regression models were compared to understand their strengths and limitations. Multiple Linear Regression provided the best balance between prediction accuracy and model complexity.

The project also strengthened understanding of gradient descent optimization, model evaluation metrics, and bias-variance concepts.
