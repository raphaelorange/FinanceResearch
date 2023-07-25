Machine Learning Project: Stock Price Analysis & Prediction

This project is focused on the application of machine learning algorithms to analyze and predict the trends of the top 50 technology companies listed on the NASDAQ from 2022 to 2023. We are working with different aspects of the dataset and applying various machine learning techniques to extract meaningful insights and forecast future stock prices.

Naive Bayes Classifier for Company Sector Determination:

In the first section, we apply a Naive Bayes Classifier to determine the sector of the companies based on the company's headquartered state and name. Insights from the boxplot visualization of Sector vs HQ State provide us with the mean number of sectors in each state and the number of companies in each sector per state. The results from this model are displayed in the model table with the predictions for the first ten rows of our dataset.

Natural Cubic Spline Fit for Volume-Price Relationship:

Next, we implement a Natural Cubic Spline Fit to understand the non-linear relationship between the volume of the NASDAQ and its close price. This is clearly illustrated in the NASDAQ Close Price VS Volume plot. The knots of our data, determined from the df 9 model, are used to explain this relationship further.

Ridge Line Regression Fit for Price Relationships:

We proceed to use a Ridge Line Regression Fit to find a relationship between the NASDAQ's open, low, high prices, and the close price. The NASDAQ Open, Low, and High Price VS Close Price plot reveals a clear linear relationship within the data. The model finds the best lambda value as 166.2234 and predicts the coefficients for the open, close, and low prices.

Multiple Linear Regression for Closing Price Prediction:

In the following section, we apply Multiple Linear Regression to predict the closing price of NASDAQ stock. We take into account the frequencies of the opening and closing stock prices. The volume of stocks and their closing prices over time also play a significant role in our predictions.

K-Nearest Neighbors for Stock Price Prediction:

We then use the K-Nearest Neighbors algorithm to compare its performance with the Multiple Linear Regression in predicting stock prices. The predicted closing prices are visualized through a scatter plot and the accuracy of the predictions is evaluated based on the R-Squared value.

Logistic Regression for Stock Buying Decision:

Finally, we implement Logistic Regression to decide whether buying NASDAQ stock is a wise decision. We categorize the stocks into two classes: 'Buy' and 'Not Buy'. The ROC curve is created from the estimate table to determine the probability that a NASDAQ stock should be bought. Our model advises on the stocks to be bought based on the current performance of the NASDAQ.

This machine learning project serves as a comprehensive guide to the application of various machine learning algorithms to understand and predict stock market trends, aiding in investment decisions.