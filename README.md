# Gold_Price_Prediction_TimeSeries_DL

## Gold Price Prediction Using LSTM, GRU, and RNN

### Overview : 
#### This project leverages advanced deep learning architectures (LSTM, GRU, and RNN) to predict gold prices using historical time-series data. The models analyze trends in gold prices from 2000 to 2024, providing insights and accurate predictions based on key financial indicators.

### Result :
#### The performance of the deep learning models—LSTM, GRU, and RNN—was thoroughly evaluated on historical gold price data, with each model being assessed based on its R² score. The LSTM model emerged as the most effective, achieving an R² score of 0.9949 on the training data and 0.9519 on the testing data, indicating its strong ability to generalize and predict unseen data. The GRU model closely followed, with an R² score of 0.9961 on training data and 0.9315 on testing data, demonstrating competitive performance. Meanwhile, the RNN model, although effective, showed slightly lower performance, with an R² score of 0.9955 on training data and 0.9091 on testing data.

#### The results underline the effectiveness of recurrent neural networks in capturing the trends and patterns of time-series data, with LSTM leading the models in accuracy. This can be attributed to its ability to retain long-term dependencies, which is critical for forecasting tasks. The testing results further reveal that the models can accurately follow the general trend of gold prices while adapting to the inherent fluctuations in the data.

#### To better illustrate the findings, detailed visualizations were created to compare the predicted and actual gold prices for all three models. These plots show that while all models managed to align with the actual values to a considerable extent, LSTM consistently provided the closest predictions, making it the optimal choice for this forecasting task.

#### The project's results confirm the suitability of deep learning techniques for time-series forecasting, especially in complex and volatile datasets like gold price trends. Below is an example visualization that showcases the models' predictions versus actual values, highlighting their effectiveness and accuracy.



### Visualization : 

![visualization.png](https://github.com/Sameh20200218AI/Gold_Price_Prediction_TimeSeries_DL/blob/main/visualization.png) 

### LSTM Result : 

![lstm_result.png](https://github.com/Sameh20200218AI/Gold_Price_Prediction_TimeSeries_DL/blob/main/lstm_result.png) 


### RNN Result : 

![rnn_result.png](https://github.com/Sameh20200218AI/Gold_Price_Prediction_TimeSeries_DL/blob/main/rnn_result.png) 


### GRU Result : 

![gru_result.png](https://github.com/Sameh20200218AI/Gold_Price_Prediction_TimeSeries_DL/blob/main/gru_result.png) 





