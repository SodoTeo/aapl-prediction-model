# Apple LSTM Prediction Model
===========================

This project contains a Long Short-Term Memory (LSTM) model that is trained to predict the stock price of Apple Inc. (AAPL). The model is implemented in Python and is run in a Jupyter Notebook.

## Requirements
------------

To run this model, you will need to have the following packages installed:

-   NumPy
-   Pandas
-   Matplotlib
-   Keras
-   Scikit-learn

You can install these packages using `pip` by running the following command:

`pip install numpy pandas matplotlib keras scikit-learn`

## Data
----

The data for this model is sourced from Nasdaq and consists of daily stock prices for AAPL from 2012 to the present. The data is split into a training set and a test set, with the training set covering the period 80% and the test set covering the remaining 20% of the dataset.

## Model
-----

The LSTM model is implemented using the Keras library and is trained using the Adam optimizer. The model is trained to predict the closing price of AAPL.

## Usage
-----

To run the model, simply open the Jupyter Notebook file `apple_lstm_prediction.ipynb` and follow the instructions in the notebook. The notebook contains code to load the data, preprocess it, train the model, and make predictions on the test set.

## Note
----

Please note that this model is for demonstration purposes only and should not be used for actual trading. Stock prices are highly volatile and predicting them with any degree of accuracy is extremely difficult. This model is not intended to be a reliable tool for making investment decisions.