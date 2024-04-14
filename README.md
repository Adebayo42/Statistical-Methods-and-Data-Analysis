# Baseball Data Analysis Project
This repository contains code and analysis for a baseball data analysis project. The project involves exploratory data analysis, simple linear regression, multiple regression for count data, and lasso regression for logistic regression. Below is an overview of the main features and findings of each part of the project:

## Project Summary
This project showcases a comprehensive analysis of baseball data using various statistical techniques and regression models. Each section provides valuable insights into different aspects of the game, from understanding salary trends to predicting division winners. The code and analysis are presented in a clear and structured manner, demonstrating proficiency in data manipulation, visualization, and modeling techniques.

## Simple Linear Regression
### Purpose: Analyzing the trend of team mean salaries over time from 1990 to 2010 and fitting a simple linear regression model to understand the relationship between mean salaries and years.
### Main Features:
- Creation of df_MeanSalaries dataset with mean salaries for each team per year.
- Visualization of team mean salaries over time and their logarithm transformations.
- Fitting a simple linear regression model to predict mean salaries based on the year.
- Evaluation of model assumptions and plotting confidence and prediction bands.

## Multiple Regression for Count Data
### Purpose: Investigating factors influencing the number of runs scored by baseball players, including player attributes, positions played, and team effects.
### Main Features:
- Creation of df_FieldingData and df_BattingData datasets for analysis.
- Construction of Poisson regression models to predict the number of runs scored.
- Analysis of predictor variables' significance using ANOVA and interpretation of results.
- Evaluation of Poisson model assumptions and consideration of team effects.
- Calculation of expected runs for specific player attributes and team in 2015.

## Lasso Regression for Logistic Regression
### Purpose: Predicting division winners in baseball using logistic regression with Lasso regularization.
### Main Features:
- Preparation of df_DivWinners dataset from 'Teams' data.
- Splitting data into training and testing sets with balanced 'DivWin' variable.
- Fitting logistic regression models using glmnet and cross-validation.
- Interpretation of model coefficients and prediction on the testing data.
- Evaluation of model performance through ROC curves and Youden's index.
- Calculation of sensitivity, specificity, and confusion matrices for model assessment.


