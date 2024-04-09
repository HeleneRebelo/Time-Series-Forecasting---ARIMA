# Time Series Forecasting
Forecasting with time series is to use past patterns to predict future values in sequential data. This involves exploratory analysis, choice of statistical models, machine learning, model tuning, and validation. The models are then used to make future predictions, although accuracy depends on the quality of the data, the choice of model, and the text applied in the model.
Here I apply the ARIMA model (Autoregressive Integrated Moving Average).


## Context
Forecast Exchange Rate End-of-period considering the euro-dollar parity.


## Main Objective
1. Predict the exchange rate (euro/dollar).


## Challenge
Making predictions with machine learning presents a series of challenges, such as overfitting and underfitting problems, and evaluating the model.


## Folder Structure
/src: Inside this folder, you will find the Notebook with the codes.


# Dataset for Time Series Forecasting
The dataset considers annual data for the period of 1991 to 2024, for 9 of the 19 Eurozone countries, each country has 6 features taken from the OECD (Organization for Economic Co-operation and Development). In addition to the 9 countries, the aggregate values of the Eurozone are also considered. 
Although, the dataset contains 6 features, to forecast the Exchange Rate I am using only this feature. To find out more read: [README.txt](https://github.com/HeleneRebelo/Time-Series-Forecasting---ARIMA/blob/main/data/README.txt.txt)


## Methodology
1. Collect data on the OECD platform
2. Check if the data is at a consistent temporal frequency, and handle missing values or outliers
3. Check the stationarity of the time series
4. This series is non-stationary in level, it was necessary to apply the first difference to make it stationary
5. Identification of ARIMA model parameters: the order of the autoregressive part (p), the order of differentiation (d), and the order of the moving average part (q)
6. Use ACF (Autocorrelation Function) and PACF (Partial Autocorrelation Function) to help identify the values of p and q
7. Fit the ARIMA model to the training data using the Maximum Likelihood and Least Squares Method to estimate model parameters
8. Evaluate the quality of the adjusted model using the AIC (Akaike Information Criterion), BIC (Bayesian Information Criterion), or mean error criterion (RMSE)
9. Check the adequacy of the model to the test data
10. Use the trained ARIMA model to make predictions
11. Evaluate the accuracy of predictions using appropriate evaluation metrics
12. Refine the model by adjusting the parameters
13. Implement the ARIMA model to make predictions
