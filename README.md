# Bond Price Prediction 

In this project we will predict trading price of bonds based on historical data. The data is provided by Benchmark solution and it is available freely on Kaggle. Here is the link to the data: - https://www.kaggle.com/c/benchmark-bond-trade-price-challenge/data

### 1. EDA
In the first notebook, `Bond_Data_EDA`, we have done some plotting to show how the bonds data is distributed. 
The line plot shows the variation of prices with number of trades. 
The histograms shows different quantities's distribution. For example, type of trade or is bond callable or not. 

### 2. Model training
In the second notebook, `Model_training_and_prediction`, we have created simple LSTM model to predict the trade price of the bond based upon the last trade data.