# Artificial Data Binary Classification

## Overview

This project implements a binary classification pipeline developed as part of a university Machine Learning course. The objective was to build a predictive model with the highest possible balanced accuracy using an artificially generated dataset containing informative features hidden among a large number of irrelevant variables.

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

1. Data validation
2. Baseline model development
3. Feature selection using Random Forest
4. Model comparison
5. Hyperparameter optimization with GridSearchCV
6. Stratified 5-fold cross-validation
7. Final model training and prediction

The preprocessing and modeling steps were implemented using a single Scikit-learn Pipeline to ensure consistent data processing and prevent data leakage.

---
## Results

The final model combined Random Forest-based feature selection with a Random Forest classifier optimized using GridSearchCV.

The selected approach achieved a mean cross-validation **Balanced Accuracy of 0.871**, substantially improving upon the baseline Logistic Regression model.

---
## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Project Status
Completed as a part of a university Machine Learning course and published as a portfolio project.

---
## Author

Maria Eberhardt

