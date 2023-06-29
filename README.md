# Stock Market Analysis with ARIMA Forecasting

This repository contains a Python script that performs stock market analysis and forecasting using the ARIMA (AutoRegressive Integrated Moving Average) model. The script loads stock market data from a CSV file, preprocesses the data, performs various analyses including trend analysis, correlation analysis, and stock price forecasting, and visualizes the results.

## Prerequisites

- Python 3.7 or above
- Required libraries: pandas, matplotlib, statsmodels, scikit-learn, seaborn

## Installation

1. Clone the repository:
git clone https://github.com/hetvipatel/stock-market-analysis.git

2. Navigate to the project directory:
cd stock-market-analysis

3. Install the required libraries:
   pip install -r requirements.txt

## Usage

1. Prepare the data:
   - Place your stock market data in CSV format in the project directory or update the file path in the code (`load_data` function).
   - Ensure that the data file includes columns for 'Date', 'Close', and 'Volume'.

2. Run the script:
   python stock_analysis.py
   
3. Interpret the results:
   - The script will display the following analyses and visualizations:
     - First few rows of the dataset
     - Information about the dataset (data types, missing values)
     - Summary statistics of the dataset
     - Line plot of the stock prices with 30-day and 50-day moving averages
     - Stock price forecasting using the ARIMA model
     - Trend analysis showing the overall trend in stock prices
     - Correlation analysis between stock prices and trading volume

4. Customize the analysis:
   - If needed, you can modify the code in the `perform_stock_forecasting`, `perform_trend_analysis`, and `perform_correlation_analysis` functions to customize the analysis and visualizations.
   - Additional parameters and settings can be adjusted as per your requirements.

## License

This project is licensed under the MIT License. Feel free to modify and use it according to your needs.

## Acknowledgements

- The script was developed using the pandas, matplotlib, statsmodels, scikit-learn, and seaborn libraries.


