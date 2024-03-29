# python

This repository contains an aggregation of some machine learning and finance-related applications utilizing python as completed during Fordham's Quantitative Finance program.

### Credit Default Prediciton
A kaggle submission for the American Express - Default Prediction competition. The goal of the competition was to predict the probability that a customer does not pay back credit card balance based on customer profile through data analysis and machine learning techniques.
https://www.kaggle.com/competitions/amex-default-prediction

### bias_variance_decomp.ipynb
An analysis on the bias/variance components of mean squared error, and their apparent decrease when more features (degrees of x) are used to estimate a continuous function.

### gradient_descent.ipynb
Two gradient descent implementations, one that performs simple gradient descent on a 3-dimensional function, and one that performs gradient descent using Newton's method on a 2-dimenstional function.

### lag_industry_returns.ipynb
An analysis exploring the predictability of monthly industry returns using lagged returns with simple linear regression and lasso regression.

### COC_CTD.ipynb
Finds the CTD T-bond using cost-of-carry method for a U.S. T-Bond future. Only bonds with 15+ years to maturity are considered. Maturity dates are rounded to the nearest .25 years.

### swaption_volatility_bootstrap.ipynb
Given prices of ATM swaptions and yield curve, creates a swaption volatility surface.
