# transformers_stock
Basic Transformer Stock Prediction

## Key Points

### Data
1. Data are all daily close prices of SPY pulled from Yahoo Finance.
2. All data are split into 5-day periods. Each period is used to predict the stock price of the next period.
3. The latest 20% of the data were used for testing, and previous data were used for training. 

### Model 
1. The model used a basic transformer encoder (customized, added layers like Conv1D to detect features).
2. The final model stacked 4 encoders and added several layers to ensure the output size was 1 x 5.

### Output
1. The mean absolute percentage error on the SPY data is roughly 2.79%.
2. The absolute relative variance between the predicted price and the true price is 0.0499.


Original Blog post: https://medium.com/@mskmay66/transformers-vs-lstm-for-stock-price-time-series-prediction-3a26fcc1a782
