# transformers_stock
Basic Transformer Stock Prediction

## Key Points

1. Data are daily close prices. All data are split into 5-day periods. Each period is used to predict the stock price of the next period.
2. The model used a basic transformer encoder (customized). The final model stacked 4 encoders and added several layers to ensure the output size was 1 x 5.
3. The mean absolute percentage error on the SPY data is roughly 2.79%, and the absolute relative variance between predicted and true is 0.0499.


Original Blog post: Reference: https://medium.com/@mskmay66/transformers-vs-lstm-for-stock-price-time-series-prediction-3a26fcc1a782
