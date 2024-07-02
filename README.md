MLP-based Neural Network Trading strategy
# Stock Trading Strategy with Neural Networks

📈 Python project for implementing a stock trading strategy using neural networks. Optimizes returns while managing risk and capital investment.

## Key Features

- **Technical Indicators**: RSI, ATR, SMA, Bollinger Bands, MACD, and Stochastic Oscillator.
- **Model**: Multi-layer Perceptron (MLP) Regressor with hyperparameter tuning.
- **Risk Management**: Uses a risk percentage and take profit threshold for trading decisions.
- **Performance Metrics**: Calculates and displays key performance metrics.
- **Visualization**: Includes functions to plot profit/loss, liquidity over time, and compare against a benchmark.
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

## Results

- **Final Balance**: $200,371.27
- **Total Return**: 0.95%
- **Annualized Return**: 1.05%
- **Volatility**: 0.21%
- **Sharpe Ratio**: 3.02
- **Max Drawdown**: -0.16%


Disclaimer
For educational purposes only. Use caution for real trading.

#StockTrading #NeuralNetworks #DataAnalysis #StockMarket #Python
