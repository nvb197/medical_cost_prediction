# Medical Cost Prediction

This project predicts medical insurance charges using **Ridge** and **Lasso** regression models. 
It includes preprocessing, feature engineering, model selection, evaluation, robustness testing, and an interactive prediction interface.

## Project Overview

- **Dataset**: `insurance.csv` 
- **Goal**: Predict individual medical insurance charges (`charges`) based on personal features.
- **Key Features**:
  - `age`, `sex`, `bmi`, `children`, `smoker`, `region`
  - Engineered features: `age_bmi`, `smoke_bmi`, `smoke_age`

- **Models**:
  - **Ridge Regression**
  - **Lasso Regression**

- **Techniques**:
  - Winsorization to handle outliers in `charges`
  - RobustScaler to scale numerical features
  - GridSearchCV to optimize regularization strength (`alpha`)
  - 5-fold Cross-Validation for model evaluation
  - Noise injection tests for robustness

---
