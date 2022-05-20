# LSTM-Stock-Predictor
In this assignment, I use deep learning recurrent neural networks to model bitcoin closing prices. One model uses the FNG indicators to predict the closing price while the second model uses a window of closing prices to predict the nth closing price.

By using the 3-layer LSTM RNN model with window size of 3, epochs of 100, and batch size of 5, I found that the model uses the closing prices has a lower loss  and tracks the actual values better over time than the model using FNG indicators. 

The model has the lowest loss when window size equals 3 and the other paremeters keep the same. 
