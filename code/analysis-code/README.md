# Statistical and Modeling Analysis Code

This folder contains all scripts related to inferential statistical testing, predictive modeling, and model tuning. These files build on the processed data and EDA outputs to perform deeper statistical investigations and machine learning.

## Files Included

-   **01_inferential_stats.qmd**\
    Performs hypothesis testing and regression analyses. Includes:
    -   Chi-square tests
    -   Logistic regression (with and without interaction terms)
    -   Odds ratio and relative risk calculations
    -   ROC curve and AUC analysis
    -   Adjusted logistic regression with confounders
-   **02_modeling.qmd**\
    Fits and evaluates predictive models:
    -   Linear regression
    -   LASSO regression
    -   Random Forest model
    -   RMSE calculations
    -   Plots predicted vs. observed values for each model
-   **03_model_tuning.qmd**\
    Conducts hyperparameter tuning for LASSO and Random Forest models:
    -   Grid search tuning without cross-validation
    -   Cross-validation tuning
    -   Visualizations of tuning performance metrics (RMSE)
