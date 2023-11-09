# Predictive_Analysis_of_Car_Prices
Predictive Analysis of Car Prices: A Data-Driven Approach using Multiple Linear Regression

## Introduction

### Multiple Linear Regression:
Multiple Linear Regression is a statistical method used to model the relationship between multiple independent variables and a dependent variable. In the context of this project, it helps predict the price of a car model based on various features such as "Age", "KM", "Horsepower (HP)", and "Weight". The method assumes a linear relationship between the independent variables and the dependent variable.

## Project Overview
The objective of this project is to predict the price of car models by employing Multiple Linear Regression. The key features considered for analysis include "Age", "KM", "Horsepower (HP)", "Weight", and other relevant attributes. The project encompasses data preprocessing, exploratory data analysis (EDA), outlier handling, and the development of a predictive model.

## Methodology

### Data Collection and Selection:
- The project begins with the collection of the dataset, followed by the selection of relevant columns essential for price prediction.

### Data Quality Check:
- A thorough check ensures the completeness of the dataset, with no missing values detected in the selected columns.

### Exploratory Data Analysis (EDA):
- Correlation analysis using a heatmap identifies strong correlations between "Price" and key variables such as "Age", "Weight", "HP", and "KM" and weak correlations with other variables.

### Outlier Handling:
- The project identifies and imputes outliers in the "Price" column, ensuring data accuracy and improving the robustness of the predictive model.

### Predictive Modeling:
- Multiple Linear Regression is employed, with "Age", "KM", "HP", and "Weight" as independent variables and "Price" as the dependent variable.

### Model Evaluation:
- The model's performance is evaluated using metrics such as R-squared (R2) score and Root Mean Squared Error (RMSE).

## Results
The predictive model achieved a significant R-squared (R2) score of 84.22, indicating a strong relationship between the selected independent variables and the car price. The Root Mean Squared Error (RMSE) value of 1162.366 further validates the model's accuracy.

## Conclusion
This project provides valuable insights into predicting car prices, offering the automotive industry a data-driven approach to optimize pricing and marketing strategies.
