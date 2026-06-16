# Income Classification Using Machine Learning

## Overview

This project develops a binary classification model to predict whether an individual's annual income exceeds $50,000 based on demographic and employment-related characteristics.

The analysis follows a complete machine learning pipeline, including data preprocessing, feature engineering, hyperparameter tuning, model comparison, and performance evaluation.

## Objective

The goal is to classify individuals into two categories:

- Income > $50K
- Income ≤ $50K

using demographic and socioeconomic variables from the Adult Income dataset.

## Data Preparation

Several preprocessing techniques were applied:

- Removal of redundant features
- Occupation grouping and feature engineering
- Missing value handling
- Categorical encoding
- Numerical feature scaling
- Stratified train-validation split (70/30)

## Models Evaluated

Three classification algorithms were trained and compared:

- Logistic Regression
- Random Forest
- XGBoost

Hyperparameter optimization was performed using:

- Randomized Search CV
- Grid Search CV
- 5-Fold Stratified Cross-Validation

## Evaluation Metrics

Models were evaluated using:

- Accuracy
- F1-Score
- ROC-AUC
- Confusion Matrix
- ROC Curve Analysis

## Results

Among the tested models, **XGBoost achieved the best overall performance**, outperforming Logistic Regression and Random Forest across all evaluation metrics.

Key findings include:

- Ensemble methods significantly improved predictive performance.
- XGBoost showed the strongest ability to identify high-income individuals.
- Cross-validation results indicated good model generalization with limited overfitting.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

## Repository Structure

```text
├── classificazione_binaria.ipynb
├── dati.csv
└── README.md
```

## Author

Laura Apicella
