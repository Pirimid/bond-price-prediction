# Bond Price Prediction 

In this project, we are predicting the trading price of bonds based on historical data. The data is provided by Benchmark solution and it is available freely on Kaggle. Here is the link to the data: - https://www.kaggle.com/c/benchmark-bond-trade-price-challenge/data

The bond market is not very much transparent compared to stock. Different brokers can give you different prices for the same bond. That is why it is necessary to understand the overall market for bonds and consider the prices. For human it is very hard to keep an eye on the whole FI market and make a decision, that is where AI systems can help us. AI systems can learn from data and can find hidden patterns into it which can help us understand the right price for the given bond. 

Given the data related to the FI market, news, tweets related to market and so on we can train an AI algorithm which can predict the price of the given bond. It will take into account the details like rating, type, last traded price, news around the bond, tweets around the bond and so on to predict the price which is right for a trader to trade. 

### 1. EDA
In the first notebook, `Bond_Data_EDA`, we have done some plotting to show how the bonds data is distributed. 
The line plot shows the variation of prices with a number of trades. 
The histograms show different quantities’ distribution. For example, the type of trade or is bond callable or not. 

### 2. Model training
In the second notebook, `Model_training_and_prediction`, we have created simple LSTM model to predict the trade price of the bond based upon the last trade data.
