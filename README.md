
# Stock Price Prediction & Forecasting

![stock](https://github.com/Fahma623/Stock-Price-Prediction-Forecasting/assets/62518284/1e2bfc8e-3eed-4271-bac5-107955de0fa0)


This project utilizes Long Short-Term Memory (LSTM) networks to predict stock prices based on historical data. LSTM networks are a type of recurrent neural network (RNN) capable of learning long-term dependencies, making them suitable for sequential data like time series.


## Overview

1. Data Preprocessing: The historical stock data (in this case, Microsoft's stock price) is preprocessed to create a windowed dataset, which is then split into training, validation, and testing sets.

2. Model Architecture: A Sequential model is built using TensorFlow's Keras API. The model comprises an LSTM layer followed by dense layers with ReLU activation functions.

3. Training: The model is trained using the training data, with validation performed at each epoch to monitor performance.

4. Evaluation: The trained model is evaluated on the validation and test sets, and predictions are compared against actual stock prices.

5. Recursive Predictions: Recursive predictions are made by feeding predicted values back into the model iteratively.
## Files Included

MSFT.csv: Historical Microsoft stock price data.
## Usage

1. Data Preparation: Ensure MSFT.csv is in the same directory as the notebook.
2. Setup Environment: Install necessary libraries (pandas, matplotlib, numpy, tensorflow).
3. Run Notebook: Execute the cells in MSFT.ipynb sequentially.
4. View Results: Analyze model performance on the training, validation, and test sets, as well as the recursive predictions.
## Requirements

Libraries: pandas, matplotlib, numpy, tensorflow
## Results

* The model demonstrates the ability to predict stock prices based on historical data.

* Performance metrics such as mean absolute error are provided for evaluation.

* Recursive predictions show the model's capability to forecast multiple steps ahead.
