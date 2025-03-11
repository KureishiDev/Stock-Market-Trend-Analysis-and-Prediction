# Stock Price Analysis and Forecasting

## Overview
This project demonstrates the analysis, forecasting, and predictive modeling of stock price data using Python. The workflow includes data collection, cleaning, exploratory data analysis (EDA), time series forecasting with ARIMA and Prophet, and predictive modeling using Linear Regression. The project uses the following libraries:

- **yfinance**: For retrieving historical stock price data.
- **pandas**: For data manipulation and cleaning.
- **matplotlib & seaborn**: For data visualization.
- **scikit-learn**: For predictive modeling using Linear Regression.
- **statsmodels**: For ARIMA time series analysis.
- **Prophet**: For time series forecasting.

## Project Structure
1. **Data Collection and Cleaning**  
    - Fetches historical stock data for AAPL from Yahoo Finance using `yfinance`.  
    - Performs basic data cleaning by removing missing values.  

2. **Exploratory Data Analysis (EDA)**  
    - Visualizes stock price trends using line plots.  
    - Calculates and plots 50-day and 200-day moving averages.  

3. **Time Series Analysis**  
    - Implements ARIMA model for forecasting future prices.  
    - Uses Prophet to generate a 30-day forecast of stock prices.  
    - Visualizes comparison between ARIMA and Prophet forecasts.  

4. **Feature Engineering**  
    - Creates lagged features to improve predictive modeling.  

5. **Predictive Modeling**  
    - Uses Linear Regression to predict stock prices based on lagged features and moving averages.  
    - Evaluates model performance using Mean Squared Error (MSE).  

## Files
- `stock_analysis.py`: Python script implementing the analysis and modeling.  
- `AAPL_stock_data.csv`: CSV file containing the historical stock data (if saved locally).  

## Requirements
Install the necessary packages with:
```bash
pip install yfinance pandas matplotlib seaborn scikit-learn statsmodels prophet
```

## Usage
Run the script to perform data analysis, forecasting, and predictive modeling:
```bash
python stock_analysis.py
```

## Future Improvements
- Include additional stock symbols for multi-stock analysis.  
- Implement more sophisticated models like LSTM and XGBoost.  
- Develop a web interface for real-time predictions and visualizations.  

## License
This project is licensed under the MIT License.
