# Rossman Sales Prediction using Prophet

This project implements a sales prediction model for Rossmann stores using Facebook's Prophet forecasting library. The goal is to predict daily sales for Rossmann stores based on historical data and various features.

## Project Overview

Rossmann operates over 3,000 drug stores in 7 European countries. This project focuses on predicting their daily sales using time series forecasting techniques. The implementation uses Facebook's Prophet library, which is particularly well-suited for business forecasting tasks.

## Dataset

The project uses the following datasets:
- `train.csv`: Historical sales data for training
- `test.csv`: Data for making predictions
- `store.csv`: Additional store information
- `submission.csv`: Sample submission file

## Project Structure

```
rossman-sales-prediction-prophet/
├── sales_prediction.ipynb    # Main Jupyter notebook with analysis and modeling
├── train.csv                 # Training dataset
├── test.csv                  # Test dataset
├── store.csv                 # Store information
└── submission.csv            # Sample submission file
```

## Model

The project uses Facebook's Prophet library for time series forecasting. Prophet is particularly effective for:
- Handling missing data
- Managing outliers
- Incorporating holidays and special events
- Automatic changepoint detection

## Results

The model's performance is evaluated using standard metrics for time series forecasting. The predictions are saved in the submission format required for the competition.
