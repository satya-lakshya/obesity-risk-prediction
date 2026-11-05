# Obesity Risk Prediction

A machine learning project that predicts obesity risk categories from lifestyle and body-measurement data.
Built as a learning project to practise a full data science workflow. More models are planned.

## What is here

- `obesity_risk_prediction.ipynb`: the notebook (preprocessing, tuning, models, comparison)
- `dataset.csv`: the dataset used

## What it does

- Cleans the data, encodes categorical features, scales numeric ones, and splits into train, validation and test sets
- Tunes base models with GridSearchCV: logistic regression, KNN, decision tree
- Builds a bagging ensemble using the best hyperparameters
- Compares model accuracy

## Status

Work in progress. Next up: AdaBoost, gradient boosting and XGBoost.

## Stack

Python, pandas, scikit-learn, Jupyter
