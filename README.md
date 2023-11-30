# Time Series Forecasting Project

## Overview

This project focuses on time series forecasting using historical sales data. The dataset includes information about invoices, stock codes, descriptions, quantities, dates, prices, customer IDs, countries, and total sales After preprocessing the dataset inclues the weekly aggregated sales

## Stationarity Test

Stationarity testing is crucial in time series analysis. Methods like the Augmented Dickey-Fuller Test are employed to assess whether statistical properties remain constant over time.

## Seasonality Analysis

Understanding seasonality patterns is essential for selecting appropriate forecasting models. Visualizations such as seasonal decomposition or autocorrelation functions aid in this analysis.

## Time Series Forecasting

Various time series forecasting algorithms are trained on the preprocessed data. These slgorithms are ARIMA, SARIMA, Simple Exponential Smoothing, Linear Regression and FFT. The goal is to predict the next 4 weeks of sales.

## Evaluation

The trained models are utilized to predict future sales values for the next 4 weeks. Evaluation metrics such as Mean Squared Error (MSE) and Mean Absolute Error (MAE) are used to assess the performance of the forecasting models.

