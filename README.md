# Stock_price_forecast_1y_1h

How to forecast 1 year, 1 hour interval stock close price?

1. Download 1 year of 1 hour period stock data
2. Filter out days without 7 data points
3. Plot Close Price versus time
4. Do LSTM on output Close Price feature, with 4 methods:
   
   a. Input Close Price as feature with 8:2 train-test split
   
   b. Input "Close", "High", "Low", "Open", "Volume" as feature with 8:2 train-test split
   
   c. Input Close Price as feature without train-test split
   
   d. Input "Close", "High", "Low", "Open", "Volume" as feature without train-test split

### I think we should use without train-test split as stock prices are volatile
