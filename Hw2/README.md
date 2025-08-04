# Assignment 2: Predictive Regressions

## Objective
Implement predictive regressions to evaluate the excess returns of the value-weighted market portfolio using a set of financial predictor variables.
To assess the predictive power of each variable by analyzing both in-sample and out-of-sample R2, as well as trying to gauge economic significance by examining the difference in the certainty equivalence (CEV) for a mean-variance investor.

## Dataset
- Data from Welch and Goyal (RFS 2008) paper, updated to the end of 2023

## Methods Used
- Univariate Predictive Regressions (Constrained and unconstrained)
- Kitchen Sink Regression (Constrained and unconstrained)
- Combination Forecasts
- Pandas, numpy, statsmodels.api

## Insights
- Combination forecasts outperformed most individual predictors in terms of OOS R^2 and CEV
- Provided higher predictive power and robustness to extreme predictions
