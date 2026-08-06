# Artificial Data Binary Classification

## Overview

This project presents a binary classification solution developed as part of a Machine Learning course. The objective was to build a predictive model with the highest possible balanced accuracy using an artificially generated dataset containing informative features hidden among a large number of irrelevant variables.

The project follows a complete machine learning workflow, including data validation, feature selection, model comparison, hyperparameter optimization and final prediction generation.

---

## Dataset

The dataset consists of:

- 1,500 training observations
- 500 test observations
- 100 numerical input features

The target variable is binary. Model performance is evaluated using **Balanced Accuracy**, making the solution robust to potential class imbalance.

---

## Objective

The main goal was to identify the most informative features and develop a classification model with strong predictive performance while minimizing the impact of noisy variables.

---

## Methodology

The project was completed using the following workflow:

1. Data validation and quality checks
2. Baseline Logistic Regression model
3. Feature selection using Random Forest feature importance
4. Comparison of multiple classification algorithms:
   - Logistic Regression
   - Random Forest
   - Gradient Boosting
5. Hyperparameter tuning using GridSearchCV
6. Stratified 5-fold Cross Validation
7. Final model training and prediction

The preprocessing and modeling steps were implemented using a single Scikit-learn Pipeline to ensure consistent data processing and prevent data leakage.

---

## Results

The best-performing solution combined:

- Random Forest feature selection
- Random Forest classifier
- Hyperparameter optimization using GridSearchCV

Cross-validation achieved a mean **Balanced Accuracy of approximately 0.87**, outperforming the baseline model.



---

## Project Status
Completed as a part of a Machine Learning course and published as a portfolio project.
## Author

Maria Eberhardt

