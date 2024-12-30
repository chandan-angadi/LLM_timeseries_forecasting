# Time-Series Forecasting of Product Sales Quantity Using local LLM

## Overview
This repository contains a Jupyter Notebook that performs time-series forecasting of product sales quantity using a Large Language Model (LLM), specifically Llama 3.2. The approach focuses on leveraging the advanced capabilities of LLMs for forecasting by using only the sales quantity feature as input, drawing inspiration from traditional ARIMA models.

## Key Features
- **Univariate Time-Series Forecasting**: Utilizes only the sales quantity feature as input for the forecasting model.
- **LLM-Powered Modeling**: Implements a forecasting approach powered by Llama 3.2 (local model), enabling sophisticated analysis and predictions.
- **Visualization**: Includes data visualizations to understand trends and seasonality.

## Notebook Contents
1. **Data Loading and Preprocessing**: Steps to prepare the sales data for time-series analysis.
2. **Exploratory Data Analysis (EDA)**: Visualization and examination of sales trends and seasonality.
3. **Model Implementation**: Applying Llama 3.2 to forecast product sales using only the sales quantity feature.
4. **Forecast Visualization**: Graphical representation of actual vs. predicted sales.

## Prerequisites
To run the notebook, ensure the following dependencies are installed:

- Python 3.7+
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- An environment supporting Llama 3.2 LLM


## Usage
- Replace the sample dataset in the notebook with your own sales data.
- Ensure the dataset has a time-index column and a sales quantity column.
- Customize the LLM parameters to fit your specific data trends.

## Limitations
- Backtesting to validate predictive accuracy is not included. (ToDo)
- Incorporating other features like discount and product meta data need to be tested in future (ToDo)

## Acknowledgments
Inspired by traditional ARIMA modeling techniques and the potential of LLMs like Llama 3.2 for univariate time-series forecasting.

