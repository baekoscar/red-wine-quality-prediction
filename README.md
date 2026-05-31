# Predicting Red Wine Quality Using Physicochemical Properties

## Overview

This project investigates whether physicochemical properties of red wine can be used to predict wine quality scores.

Using a dataset of 1,143 red wine samples from Kaggle, I performed exploratory data analysis and developed multiple predictive models in R using the tidymodels framework.

## Dataset

Source: Kaggle Wine Quality Dataset

Variables include:

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality Score (Target Variable)

## Methods

### Exploratory Data Analysis

- Distribution of wine quality scores
- Alcohol vs. quality analysis
- Volatile acidity vs. quality analysis
- Correlation analysis

### Machine Learning Models

- Linear Regression
- Lasso Regression
- Decision Tree Regression

Models were trained and evaluated using the tidymodels ecosystem.

## Results

Model performance was compared using RMSE on a held-out test set.

| Model | RMSE |
|---------|---------|
| Linear Regression | 0.638 |
| Lasso Regression | 0.639 |
| Decision Tree | 0.668 |

Linear Regression produced the best predictive performance.

## Technologies Used

- R
- Quarto / R Markdown
- tidyverse
- tidymodels
- glmnet
- rpart
- corrplot

## Author

Oscar Baek

University of California, Santa Barbara

Economics & Data Science
