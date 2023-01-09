# Yesbank-stock-pricing-analysis-regression-model
**ML regression project**

A stock (also known as equity) is a security that represents the ownership of a fraction of a corporation. This entitles the owner of the stock to a proportion of the corporation's assets and profits equal to how much stock they own. Units of stock are called "shares."
The value of shares depends on the investors, whether more people are buying the stock or selling it, follows the simple supply – demand rule. 

So my project was to apply different regression models on the given data to predict the closing price of the stock, then compare all the models to figure out the best one for this job. 

I started off with data overview, just to understand what’s in the dataset and plan out the steps to get the final result. 

Next step was to perform EDA, do the required feature engineering steps and carry out univariate/bivariate analysis.

In the next step, I split the data into train and test data set and ran the following regression models-
1.	Linear regression
2.	Lasso regression
3.	Ridge regBased on the open vs. close price graph, we concluded that Yes Bank's stock fell significantly after 2018.
4.	KNN
5.	XGBoost

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
