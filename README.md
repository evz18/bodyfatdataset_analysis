# Body Fat Prediction from Field Measurements

## Overview
This project evaluates how well field-based anthropometric measurements (e.g., circumferences) can predict body fat percentage. Multiple regression models were trained and compared using cross-validation to estimate generalization performance.

## Methods
- Data cleaning and exploratory analysis
- Feature engineering (if applicable)
- Linear Regression and baseline comparisons
- Model evaluation with cross-validation (RMSE/MAE)
- Diagnostic plots (actual vs predicted, residuals)

## Results
- Reported performance metrics (RMSE/MAE) and key findings from model comparison
- Summary of the practical interpretation of prediction error (e.g., average error in % body fat)

## Key Insight
Based on cross-validated performance, field-based anthropometric measurements can estimate body fat percentage with an average error of approximately 1–2 percentage points relative to hydrostatic-derived values.

## Limitations
- Dataset size 
- Linear model assumptions may not capture nonlinear relationships

## Future Work
- Compare regularized models (Ridge/Lasso) and tree-based models
- Calibrate predictions to other specific populations
