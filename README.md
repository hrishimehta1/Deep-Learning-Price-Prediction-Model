MLP-based Neural Network Trading strategy
# Stock Trading Strategy with Neural Networks

📈 Python project for implementing a stock trading strategy using neural networks. Optimizes returns while managing risk and capital investment.

## Key Features
- **Neural Network Model**: Utilizes a Multi-Layer Perceptron (MLP) regression model from Scikit-Learn to predict stock price movements.
- **Data Preprocessing**: Prepares historical stock price data, calculates technical indicators (RSI, ATR, SMA, Bollinger Bands).
- **Risk Management**: Manages capital investment and sets take-profit thresholds.
- **Trading Signals**: Generates buy and sell signals based on predictions.
- **Performance Metrics**: Evaluates strategy performance, including capital invested, profit/loss, total return.
- **Trade Information**: Provides detailed trade data.

## Usage
1. Define `ticker`, `start_date`, and `end_date`.
2. Create an instance of `NeuralNetworkStrategy`.
3. Call `run()` to execute the strategy.
4. Use `get_trade_info()` to access trade details.

## Requirements
- Python
- NumPy
- Pandas
- Scikit-Learn
- Matplotlib
- Yfinance

## Example Usage
```python
if __name__ == '__main__':
    ticker = 'AAPL'
    start_date = '2023-07-31'
    end_date = '2023-09-30'
    strategy = NeuralNetworkStrategy(ticker, start_date, end_date)
    strategy.run()
    trade_info = strategy.get_trade_info()
    
    # Display trade information
    for info in trade_info:
        ...


Disclaimer
For educational purposes only. Use caution for real trading.

#StockTrading #NeuralNetworks #DataAnalysis #StockMarket #Python
