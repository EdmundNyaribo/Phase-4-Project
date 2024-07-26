# Dream House International
## Zillow Real Estate Time Series Analysis


### OVERVIEW
This project involves building a time series model using Zillow data  from Zillow Research to aid real estate investors in making informed investment decisions. The dataset comprises property information, and the project encompasses data preprocessing, time series transformation, exploratory data analysis, model selection, training, and evaluation. The model's objective is to forecast property price trends, which will be presented to investors through a user-friendly interface. Recommendations on where to invest will be provided based on these predictions and supplemented with additional insights from EDA. The project also includes documentation, deployment, maintenance, and a feedback loop to continuously enhance the model's accuracy and relevance to real estate investment needs.


### BUSINESS UNDERSTANDING
Following its success in the real estate business over the years, Dream House International, a real estate agency, has provided housing solutions to many of the people living in the United States. Dream House International now wants to expand its reach further in the existing states but want to focus in the best ones for further investment. Using the Zillow dataset, this project aims to determine the best 5 investment opportunities for Dream House International.


### Objectives
1. To identify the top 5 best states for Dream House International to invest in.
2. To identify the top 5 states with the highest ROI(Return on Investment).
3. To forecast future real estate prices for the zip codes over various time horizons.


### DATA UNDERSTANDING AND PREPARATION
For data understanding and preparation, begin by thoroughly exploring the Zillow dataset, checking for missing values, and addressing outliers. Changing the dataset from wide format to long format.Transform the dataset into a time series format, with 'RegionName' representing unique properties or regions and 'Date' as the time dimension. Calculate relevant time-based features, such as moving averages or seasonality patterns, to capture temporal trends. Additionally, split the data into training and testing sets, reserving the most recent data for validation. This will create a clean, structured dataset ready for time series modeling and forecasting.


### PROJECT OBJECTIVE
The project's main objective is to develop a time series forecasting model using Zillow data to assist real estate investors in making informed decisions about where to invest their capital. This model will provide predictions and insights into property price trends over time, helping investors identify regions and cities with potential for price appreciation. Ultimately, the project aims to empower investors with data-driven tools that enhance their understanding of real estate market dynamics, enabling them to make more strategic and profitable investment choices. The key question being:What are the top 5 best zip codes for us to invest in.


### MODELLING
The following models were used during the developing of a machine learning model that can predict what are the top 5 best zip codes for us to invest in.This model will provide predictions and insights into property price trends over time, helping investors identify regions and cities with potential for price appreciation. Ultimately, the project aims to empower investors with data-driven tools that enhance their understanding of real estate market dynamics, enabling them to make more strategic and profitable investment choices.

* The base model is simple and serves as a benchmark.
* The ARIMA model involves identifying the order of differencing, autoregression, and moving average components to handle          non-seasonal data.
* The SARIMA model extends ARIMA by incorporating seasonality, improving forecast accuracy for seasonal time series data.


### EVALUATION
In this project, multiple evaluation metrics were used to assess the performance of different models in predicting the top 5 best zip codes to invest in. 

* MSE (Mean Squared Error): Measures the average of the squares of the errors.
* RMSE (Root Mean Squared Error): Square root of MSE, providing error magnitude in the same units as the original data.
* Compare multiple ARIMA models using AIC (Akaike Information Criterion) and select the model with the lowest AIC.


### CONCLUSION
Based on the evaluation metrics (MSE and RMSE), the SARIMA outperformed other models with the lowest RMSE. This model was selected as the final model for predicting best zip codes to invest in.The following are the results of the metrics used during he modeling:
* Base Model: Serves as a baseline, expected to have higher MSE and RMSE compared to ARIMA and SARIMA.
* ARIMA Model: Expected to perform better than the base model by capturing non-seasonal patterns.
* SARIMA Model: Expected to perform the best if there is seasonality in the data, by capturing both non-seasonal and seasonal     patterns.

The top 5 best zip codes to invest in:
1. California
2. New York
3. Texas
4. Pennsylvania
5. Florida


### For More Information
Please review my full analysis in my Jupyter Notebook or my Presentation

```python

```
