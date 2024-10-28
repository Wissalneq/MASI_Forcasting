# MASI Index Forecasting

## Project Overview
This project focuses on forecasting the Moroccan All Shares Index (MASI) using three time-series models: Artificial Neural Network (ANN), Autoregressive Integrated Moving Average (ARIMA), and Long Short-Term Memory (LSTM) neural networks. The MASI index is a key indicator of the Moroccan stock market's overall performance, and accurately predicting its trends can provide valuable insights for investors and stakeholders.

## Objectives
- Build predictive models using ANN, ARIMA, and LSTM for forecasting the MASI index.
- Compare the performance of these models in terms of accuracy and efficiency.
- Evaluate each model's ability to capture patterns in stock market data and deliver reliable forecasts.

## Dataset
The dataset consists of historical MASI index values over a specified time period, including daily closing prices and other relevant features.

- **Source**: [Add data source link here if available]
- **Features**: Date, Closing Price, Volume, etc.
- **Preprocessing**: Includes normalization, handling missing values, and train-test splitting.

## Methodology

### Models
- **ARIMA**: A statistical model used for time-series forecasting. This model requires making the series stationary and tuning parameters (p, d, q) for optimal performance.
- **Artificial Neural Network (ANN)**: A feed-forward neural network designed to capture non-linear relationships in time-series data, using lagged values of the MASI index for training.
- **Long Short-Term Memory (LSTM)**: A recurrent neural network (RNN) model effective for sequential data, capturing temporal dependencies and long-term trends.

### Implementation
Implemented in Python with the following libraries:
- **TensorFlow/Keras** for ANN and LSTM models
- **Statsmodels** for ARIMA
- **Pandas, Numpy, and Matplotlib** for data handling and visualization.

## Results
The models are evaluated based on forecasting accuracy, using metrics like Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and Mean Absolute Percentage Error (MAPE). Performance comparisons highlight the strengths and weaknesses of each approach.
