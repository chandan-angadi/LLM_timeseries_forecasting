# Time-Series Forecasting of Product Sales Quantity

## Overview
This repository contains a Jupyter Notebook that performs time-series forecasting of product sales quantity. The approach focuses on using only the sales quantity feature as input, similar to the methodology employed in ARIMA models. The aim is to explore and implement a simple yet effective forecasting technique, suitable for scenarios where minimal input features are available.

## Key Features
- **Univariate Time-Series Forecasting**: Utilizes only the sales quantity feature as input for the forecasting model.
- **ARIMA-Like Approach**: Implements techniques inspired by the ARIMA model, leveraging the temporal dependencies within the sales data.
- **Visualization**: Includes data visualizations to understand trends and seasonality.

## Notebook Contents
1. **Data Loading and Preprocessing**: Steps to prepare the sales data for time-series analysis.
2. **Exploratory Data Analysis (EDA)**: Visualization and examination of sales trends and seasonality.
3. **Model Implementation**: Applying a forecasting model that mimics ARIMA’s functionality with only sales quantity as input.
4. **Forecast Visualization**: Graphical representation of actual vs. predicted sales.

## Prerequisites
To run the notebook, ensure the following dependencies are installed:

- Python 3.7+
- Jupyter Notebook
- pandas
- numpy
- matplotlib

## Usage
- Replace the sample dataset in the notebook with your own sales data.
- Ensure the dataset has a time-index column and a sales quantity column.
- Customize the model parameters to fit your specific data trends.

## Future Enhancements
- Incorporate evaluation metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) to assess model performance.
- Add backtesting to validate the model's predictive accuracy.
- Explore multivariate time-series forecasting by adding additional features such as pricing, promotions, or external factors.
- Experiment with other advanced models like LSTM or Prophet.
- Automate hyperparameter tuning for improved performance.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
Inspired by traditional ARIMA modeling techniques and the simplicity of univariate forecasting approaches.
