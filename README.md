# FinBERT Stock Trading Bot Test

This project demonstrates a basic implementation of a stock trading backtest using machine learning. The backtesting framework utilizes the Alpaca API for trading and Yahoo Finance for historical data. The machine learning model is implemented using the FinBERT sentiment analysis model.

## Project Structure

- **tradingbot.py**: Python script containing the main logic for the trading strategy and backtesting. It uses the Alpaca API for trading, Yahoo Finance for historical data, and the FinBERT model for sentiment analysis.

- **finbert_utils.py**: Python script containing utility functions for the FinBERT sentiment analysis model.

## Requirements

- Python 3.x
- Libraries listed in the `requirements.txt` file.

## Getting Started

1. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

2. Set up your Alpaca API key and secret as environment variables:

    ```bash
    set ALPACA_API_KEY=your_api_key
    set ALPACA_API_SECRET=your_api_secret
    ```

3. Run the `tradingbot.py` script to perform backtesting:

    ```bash
    python tradingbot.py
    ```

## How to Use

1. Modify the `tradingbot.py` script to adjust trading parameters, such as the symbol, cash at risk, and trading strategy.

2. Ensure that the required environment variables (`ALPACA_API_KEY` and `ALPACA_API_SECRET`) are set.

3. Run the script to backtest the trading strategy over a specified date range.

## Notes

- The trading strategy in `tradingbot.py` uses a basic sentiment analysis approach to make buy/sell decisions based on news sentiment.

- The machine learning model (`finbert_utils.py`) is a sentiment analysis model specifically trained for financial news.

- This project is a starting point for exploring and getting familiar with stock trading APIs and integrating them with machine learning for backtesting purposes.

## Future Improvements

- Explore and implement more sophisticated trading strategies.

- Integrate real-time data for live trading.

- Add more detailed documentation for better understanding and customization.