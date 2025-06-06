# Stock Price Prediction Using LSTM in PyTorch
Long Short-Term Memory (LSTM) model to predict future stock prices using historical closing price data. The model is built using PyTorch and trained on Apple's (AAPL) stock data fetched from Yahoo Finance.

# Features
- Data fetched using yfinance and normalized using StandardScaler
- Time series data preparation with sliding windows
- LSTM-based regression model using PyTorch
- Evaluation using RMSE and inverse scaling of predictions
- Visualizations of predicted vs actual stock prices

# Libraries Used
- PyTorch
- NumPy, Pandas
- Scikit-learn
- Matplotlib
- yFinance
