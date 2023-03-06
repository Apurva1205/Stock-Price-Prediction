# Stock-Price-Prediction


The code loads historical data of Nifty50 index from a CSV file using Pandas library.
The Date column in the CSV file is converted to datetime format and set as the index for the data frame.
The closing price column is extracted and plotted using Matplotlib library.
The data is split into training and testing sets. The last 30 days of data is kept aside for testing.
An ARMA model is fit to the training data using the ARIMA function from Statsmodels library.
The model is used to predict the closing price for the next day using the forecast function.
The ARMA model is fit to the training data again.
The model is used to predict the closing price for each day in the testing set using the forecast function.
The root mean squared error (RMSE) is calculated to evaluate the accuracy of the predictions.
The profit/loss is calculated by subtracting the first predicted price from the first actual price in the testing set.
A function is defined to predict the next day's closing price for any stock symbol using the same ARMA model. The function downloads the historical data for the specified stock from Yahoo Finance, fits the ARMA model to the entire data, and uses it to predict the next day's closing price.
I hope this helps!





