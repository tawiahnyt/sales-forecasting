<!-- @format -->

# FMCG Sales Forecasting Application

This application implements multiple machine learning models for forecasting sales volumes in the FMCG (Fast-Moving Consumer Goods) sector. It combines traditional time series analysis with modern machine learning approaches to provide accurate sales predictions.

## Models Implemented

1. SARIMA (Seasonal ARIMA)

   - Captures temporal patterns and seasonality
   - Handles time-dependent patterns in sales data

2. XGBoost Regression

   - Incorporates multiple features including price, promotions, and inventory
   - Captures non-linear relationships in the data

3. LSTM (Long Short-Term Memory)
   - Deep learning approach for complex pattern recognition
   - Handles long-term dependencies in time series data

## Features

- Comprehensive data preprocessing
- Feature engineering including temporal features
- Model performance evaluation using RMSE, MAE, and R-squared metrics
- Market share prediction capabilities
- Synthetic data validation

## Setup

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Run the application:

```bash
python sales_forecasting.py
```

## Data Requirements

The application expects a CSV file with the following columns:

- Date
- Product_Category
- Sales_Volume
- Price
- Promotion
- Store_Location
- Weekday
- Supplier_Cost
- Replenishment_Lead_Time
- Stock_Level

## Model Evaluation

The system automatically evaluates and compares the performance of all implemented models using:

- Root Mean Square Error (RMSE)
- Mean Absolute Error (MAE)
- R-squared (R²) score
# sales-forecasting
