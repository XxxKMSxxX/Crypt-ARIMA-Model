# Bitcoin Price Prediction using SARIMA Model

This Python program predicts the future price of Bitcoin using the Seasonal AutoRegressive Integrated Moving Average (SARIMA) model. The program downloads historical Bitcoin price data from Yahoo Finance, processes the data, and trains the SARIMA model to make future price predictions.

## Requirements

To run the program, you will need Python 3.x installed and the following libraries:

- pandas
- yfinance
- pmdarima
- matplotlib

You can install the required libraries using `pip`:

```py
pip install pandas yfinance pmdarima matplotlib
```

## How to Run the Program

1. Save the program as `bitcoin_price_prediction.py`.
2. Open a terminal or command prompt.
3. Navigate to the directory where the `bitcoin_price_prediction.py` file is saved.
4. Run the following command:

```py
python bitcoin_price_prediction.py
```

The program will output the actual vs. predicted prices plot and the future predictions with confidence intervals.

## Program Structure

The program consists of the following functions:

- `get_data()`: Downloads historical price data from Yahoo Finance.
- `preprocess_data()`: Preprocesses the data, including resampling and normalization.
- `predict_price()`: Trains the SARIMA model and makes future price predictions.
- `main`: Main function that calls the other functions and outputs the results.

## Disclaimer

This program is for educational purposes only. The predictions made by the program are not guaranteed to be accurate and should not be used for investment decisions. Always do your research and consult with a financial advisor before making any investment decisions.
