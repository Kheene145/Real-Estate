# House Price Prediction

# Project Overview

This project analyzes housing data to predict property prices using machine learning techniques. The dataset consists of 1,460 observations with a mix of numerical and categorical variables describing property characteristics, location, and quality.
The goal is to develop models that can accurately estimate sale prices and evaluate their performance using statistical metrics.

📊 Dataset

Source: Provided dataset (1,460 entries)

Shape: 1,460 observations × multiple features (numerical + categorical)

Target Variable: SalePrice

Feature Types:

Numerical: OverallQual, Lot area, year built, living area, garage size, number of rooms, etc.

Categorical: Neighborhood, building type, overall quality, exterior material, etc.

#  Methodology

Data Cleaning & Preprocessing

Handled missing values (imputation with median/mode or domain logic)

Encoded categorical variables (label encoding, one-hot encoding)

Applied transformations to skewed variables

Exploratory Data Analysis (EDA)

Distribution of house prices

Correlation heatmap of features vs target

Feature importance from tree-based models

# . Model Development

Data Splitting

Split dataset into 80% training and 20% testing sets.

Model Selection

Simple Baseline: Simple Linear Regression using only OverallQual to predict SalePrice.
The non-linear nature of Random Forest helps capture complex interactions between quality and price.


# Evaluation Metrics

Mean Squared Error (MSE): Measures prediction error magnitude

R-squared: Explains variance captured by the model

📈 Results / Findings

Linear Regression: Provided baseline results with moderate accuracy.

Random Forest Regressor: Improved predictions by modeling non-linear relationships.

Gradient Boosting Regressor: Achieved the best performance with the lowest error and highest R-Squared score.


# Limitations

Dataset limited to 1,460 properties — may not fully generalize to other markets.

Outliers in SalePrice still impact predictions.

