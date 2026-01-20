# Linear Regression From Scratch

This project implements **Simple Linear Regression from scratch** using **gradient descent**, without relying on `sklearn` for training.

## Problem Statement
Given a dataset containing **Years of Experience** and corresponding **Salary**, build a machine learning model to predict salary for new experience values.

## Dataset
- Source: Salary dataset
- Features: Years of Experience
- Target: Salary

## Approach
- Manual data normalization
- Custom train-test split
- Gradient Descent optimization
- Loss function: Mean Squared Error (MSE)

## Model Equation
y = wx + b

Where:
- w = weight
- b = bias

## Features
- Linear Regression implemented from scratch
- No sklearn used for training
- Custom evaluation metrics (MSE, RMSE, R²)
- Visualization of regression line and loss curve
- Comparison with sklearn LinearRegression

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook Linear_Regression_From_Scratch.ipynb
