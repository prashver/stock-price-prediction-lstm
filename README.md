# Stock Price Prediction of Nestle India Using Recurrent Neural Network
Using Recurrent Neural Network (RNN) and Long Short-Term Memory (LSTM) to predict the stock prices of Nestle India.

# Dataset
The dataset is taken from NSE India's website in CSV format. The dataset consists of Open, High, Low and Closing Prices of Nestle India stocks from 18th May, 2018 to 20th May, 2022 - total 1486 rows.

# Architecture
The architecture of the RNN is 4 sets of LSTM (Long Short Term Memory) layers and Dropout regularization layers with the LSTM and Dropout layers sandwitched between each other. The number of time steps chosen for the RNN is 60. The model is trained on 100 epochs with a batch size of 32. The optimizer used is adam and the loss function is mean squared error.

# Results
After successful prediction, the results were visualized using the matplotlib library.

