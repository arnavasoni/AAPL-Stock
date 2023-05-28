# Stock Price Prediction

Predicting Apple's stock closing price, using data collected from 2015 to 2020.

## Libraries Used:
* Pandas to work with the data provided.
* Numpy to mathematically work on the data.
* Scikit Learn for processing the data and using the Linear Regression model.
* Plotly to make candlestick graphs for the collected data.
* datetime to work with date and time as per requirement.

## Overview:
* Read the CSV.
* Plot the candlestick graph.
* Define a method that handles data preprocessing.
* Convert the required column/attribute to an array, so that scaling can be performed.
* Clean the column of any null values.
* Split the data for training and testing.
* Mention the feature column, number of predictions to be made, and the train test split percentage.
* Train the model using training data.
* Check how well the model is working using model.score()
* Predict the values.
* Print as a dataframe.
