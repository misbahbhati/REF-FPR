Apple Stock Price Prediction

Overview:

This project analyzes historical Apple (AAPL) stock data and builds predictive models to forecast future closing prices. The models used include ARIMA (AutoRegressive Integrated Moving Average), SARIMA (Seasonal ARIMA), and LSTM (Long Short-Term Memory) neural networks. The data is fetched from Yahoo Finance using the yfinance library, covering the period from January 1, 2010, to January 1, 2024.

The notebook performs:

Data downloading and preprocessing.
Exploratory Data Analysis (EDA), including visualizations of closing prices over time.
Model training and evaluation for ARIMA and SARIMA.
Comparison of predictions from ARIMA and SARIMA models.
This is a final year project (FYP) demonstrating time series forecasting techniques on financial data.

Requirements

Python 3.11 (tested on 3.11.5)
Jupyter Notebook or JupyterLab
Libraries:
yfinance (for data fetching)
pandas (for data manipulation)
matplotlib and seaborn (for visualizations)
statsmodels (for ARIMA/SARIMA models)
tensorflow or keras (for LSTM models)
Other dependencies: numpy, scikit-learn (used for metrics)
Usage

Open the Jupyter notebook
Run the cells sequentially:

The first section downloads the Apple stock data and saves it as apple_stock_data.csv.
EDA sections generate plots for stock trends.
Model sections train ARIMA, SARIMA, and LSTM models, then visualize predictions.

Outputs include:

Data summaries and info.
Plots of actual vs. predicted prices.
Evaluation metrics (e.g., MSE, RMSE) for model performance.

Results

ARIMA/SARIMA: Suitable for stationary time series; SARIMA handles seasonality better.

LSTM: Captures long-term dependencies in non-linear data, often outperforming traditional models on financial time series.

Example Plot: The notebook generates a comparison plot of ARIMA vs. SARIMA predictions against actual test data.

For detailed results, refer to the notebook outputs. Predictions are visualized in matplotlib figures.

Limitations

Stock prices are influenced by external factors (e.g., market news, economic events) not captured in historical data alone.

Models assume stationarity; real-world data may require additional transformations.

Clone repository :https://github.com/misbahbhati/REF-FPR/blob/main/Final_FYP%20(3).ipynb

