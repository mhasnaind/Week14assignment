# Week14 Assignment: Machine Learning

**This assignment required us to use the Long Short Term Memory (LSTM) Recurrent Neural Networks (RNN) model for two scenarios: Predicting bitcoin price using Fear and Greed (FNG) values and a window of bitcoin closing prices to predict the nth closing price. 

1) The model using a window of closing prices displayed lower loss of 0.0146 on scaled values compared to a loss of 0.077 for FNG model.
2) The bitcoin closing price model tracks the actual values a lot better than the FNG model. Having said that, it's still not a good model given the discrepancy in bitcoin price prediction. A better way to do it would be to use percentage change as opposed to closing prices.
3) The 30 day window size provides a much more accurate prediction for bitcoin closing price compared to the 10 day window.
