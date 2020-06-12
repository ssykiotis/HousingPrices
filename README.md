# HousingPrices
This repository contains my solution to Kaggle's Housing Prices: Advanced Regression Techniques competition. My solution is focused on getting extensive insight into the data in order to develop meaningful strategies for filling in the missing data and fixing data abnormalities.

After data cleaning is performed, an ensemble regression model is developed that consists of 5 individual regressors. Their predictions are averaged in order to obtain the final prediction. This tecnhique achieves reasonably good results on the dataset and got me placed in the top 12% amongst all competition participants.


Repository contents:

* data: training and test data files
* housing_prices.ipynb: Jupyter notebbok containing the solution

The solution is structured as follows:

1. Environment Setup
2. Data Exploration
3. Data Cleaning
4. Model Training 
5. Results


The regressors that are ensembled are: 

* Lasso
* ElasticNet
* Ridge Regression
* Gradient Boosting Regression
* XGBoost Regressor
* LightGBM Regressor
