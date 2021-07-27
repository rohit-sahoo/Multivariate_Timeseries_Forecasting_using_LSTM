# Multivariate_Timeseries_Forecasting_using_LSTM

Time-Series forecasting means predicting the future dependent variable (y) based on the past independent variable (x). If the model predicts a dependent variable (y) based on one independent variable (x), it is called univariate forecasting. Whereas, In Multivariate forecasting, the model predicts a dependent variable (y) based on more than one independent variable (x).

This Example implements a time series model for Google's stock market data. In this example, Multivariate time series forecasting is performed by determining the opening price of the stock using the historical opening, closing, highest, lowest and the adjusted closing price. This example uses the LSTM (Long Short-Term Memory) model to predict the opening price of the stock by taking the input shape defined by the window length and these 5 features.

A univariable forecast model reduces this complexity to a minimum – a single factor and ignores the other dimensions such as prediction of the opening price of the stock is based only on the historical opening price. Whereas, A multivariate stock market prediction model can consider the relationship between multiple variables. They offer a more detailed abstraction of reality than univariate models. Multivariate models thus tend to provide more accurate predictions than univariate models.

## Dataset
This example uses Google's stock market dataset downloaded from [Yahoo
Finance](https://in.finance.yahoo.com/quote/GOOG/history?period1=1092960000&period2=1594944000&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true)


**Time-Frame Considered:** 16 Years of data starting from 2004/08/19 to 2020/07/17.

**Structure of Dataset**

1. Date - specifies trading date
2. Open - opening price
3. High - maximum price during the day
4. Low - minimum price during the day
5. Close - close price adjusted for splits
6. Adj Close - adjusted close price adjusted for both dividends and splits
7. Volume - the number of shares that changed hands during a given day

