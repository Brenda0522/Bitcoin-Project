This project aims to explore Bitcoin price predictability in the cryptomarket.

Daily data was collected for a year and hourly data was collected for 15985 data points. An LSTM model was performed to study both daily and hourly data, hyperparameter tuning was performed, and price was predicted for the next 10 time units. 

The absolute.ipynb file contains absolute price predicted, and the change.ipynb file handles the price change between time units attempting to make a more precise prediction considering the content of "moving average" for Time Series data.
