# Kalman Filter for Stock Price Estimation

A Python project applying a **Linear Kalman Filter** to estimate the true underlying
trend of a noisy stock price series, benchmarked against a 20-day Moving Average.

## Motivation
Having built an **Extended Kalman Filter** for robot state estimation in MATLAB,
this project applies the same mathematical framework to financial time series —
demonstrating cross-domain transferability of state estimation concepts.

## Results
| Metric | Kalman Filter | Moving Average |
|--------|--------------|----------------|
| MAE    | 1.1832       | 4.8089         |
| RMSE   | 1.5367       | 5.7520         |
| Std Dev| 1.5364       | 5.2825         |

The Kalman Filter tracks the true price ~4x more accurately than a Moving Average.

## Tech Stack
Python, NumPy, Pandas, Matplotlib, yfinance, filterpy

## Resume Keywords
Kalman Filter · State Estimation · Signal Processing · Time-Series Filtering · Sensor Fusion · Financial Modeling