# Yesbank-stock-pricing-analysis-regression-model
<img src="https://upload.wikimedia.org/wikipedia/en/thumb/8/85/Yes_Bank_logo.svg/1200px-Yes_Bank_logo.svg.png" width="600" height="200">
<h1>About Project:-</h1>
Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock’s closing price of the month.

<h2>ABSTRACT:</h2>
Accurate prediction of stock market returns is a very challenging task due to the volatile and non-linear nature of the financial stock markets. With the introduction of machine learning, time series forecasting, and increased computational capabilities, programmed methods of prediction have proved to be more efficient in predicting stock prices.
In this work, regression and time series forecasting techniques have been utilized for predicting the next day closing price for one company belonging to the Finance sector of operation.
The financial data: Open, High, Low, and Close prices of stock are used for creating new variables which are used as inputs to the model.
The models are evaluated using standard strategic indicators: RMSE and MAPE.
The low values of these two indicators show that the models are efficient in predicting stock closing prices.

<h3>The Yes Bank Data is first extracted and then categorized to identify, analyze behavior data and patterns. Using this dataset in our Supervised ML-Regression project we found some relevant analysis which would help to predict the monthly stock’s closing price of Yes Bank to perform better. </h3>

*	**Data set** - data_YesBank_StockPrices - contains observations regarding open, close, high and low prices of the yes bank stock from July 2005 – November 2020.
*	**Rows:** 185 
*	**Column:** 5 
*	**Date:** It denotes the month and year for a particular price. 
*	**Open:** Open means the price at which a stock started trading that month. 
*	**High:** refers to the maximum price that month. 
*	**Low:** refers to the minimum price that month. 
*	**Close:** refers to the final trading price for that month, which we have to predict using regression technique. 

<h3>The objective of this project is to predict the stock’s closing price of the month. Discussion of Yes Bank Dataset will involve various steps such as:</h3> 

1.	Loading the data into data frame 
2.	Cleaning the data 
3.	Extracting statistics from the dataset 
4.	Exploratory analysis and visualizations
5.	Train Test Split 
6.	Linear Regression 
7.	Lasso Regression 
8.	Ridge Regression 
9.	XGBoost Regression 

I also saved all the evaluation metrics in a data frame.
In the end, I compared all the metrics and came to the following conclusions-

1. The target variable is highly dependent on input variables.
2. Linear Regression has given the best results with lowest MAE, MSE, RMSE and MAPE scores.
3. Ridge regression shrunk the parameters to reduce complexity and multicollinearity, but ended up   affecting the evaluation metrics.
4. Lasso regression did feature selection and ended up giving up worse results than ridge which again reflects the fact that each feature is important (as previously discussed).
5. KNN AND XGBoost have given similar results.
6. The trend of the price of Yes Bank's stock increased until 2018 and then Close,Open,High,Low price decreased.
7. Based on the open vs. close price graph, we concluded that Yes Bank's stock fell significantly after 2018.
8. Visualization has allowed us to notice that the closing price of the stock has suddenly fallen starting in 2018. It seems reasonable that the Yes Bank stock price was significantly impacted by the Rana Kapoor case fraud.
