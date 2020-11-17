# Stock Market Prediction using Financial News Sentiment and Neural Network Models


## Overview:

We develop tools for time series forecasting using sentiment analysis and various neural network models.
We build a few different styles of models including Convolutional and Recurrent Neural Networks (CNNs and RNNs). We combine ”public sentiment” and historical market data to find a predictor for ”market movment”. We use financial news datasets from Reuters to predict public mood given by the sentiment of the news headline. In addition, we use Dow Jones Industrial average closing price to predict next day movement. The model trained with time series features for the period '2006-10-20' to '2008-01-17' obtain ~%95 accuracy on the test set from '2008-01-17' to '2008-02-28 using the window size of 32 days. We also compare the perf

Data Sets:
Reuters Finacial News Data Set: https://github.com/duynht/financial-news-dataset
Dow Jones Industrial average data from yfinance

![plots](https://github.com/kochoravi/news-sentiment-stock-prediction/blob/master/DJI-prediction-plots.png?raw=true)

![plots](https://github.com/kochoravi/news-sentiment-stock-prediction/blob/master/wc-topis-plot.png?raw=true)

## Summery:

Financial news data prepration, topic modeling and sentiment analysis

Clean, standardize and merging financial news sentiment and DJI avg. price data

Compare the performance of neural network models and some baseline.

Visualizing the news sentiment and the historical data

Time series preperation and training/evaluation of the LSTM network 

