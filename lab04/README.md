# Titanic Fare Prediction

This project explores how well passenger characteristics can predict fare prices in the Titanic dataset.

## Objective

The main objective is to evaluate how well different regression models can predict the "Fare" column based on available passenger data, and to understand the limitations and effects of using binary categorical features like "Sex" in regression tasks.

## Features Used

- `Sex` (encoded as binary: 0 or 1)
- Other potential features (e.g., `Pclass`, `Age`, etc.) were considered but not included in the primary analysis.

## Models Evaluated

- Linear Regression
- Ridge Regression
- ElasticNet Regression
- Polynomial Regression

## Key Findings

- "Sex" had some predictive power, but performance was limited.
- Linear, Ridge, and Polynomial regressions performed identically.
- ElasticNet slightly underperformed compared to the others.
- Outliers and skew in the fare data negatively impacted model accuracy.