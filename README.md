# Electric Vehicle (EV) Registration Forecasting

This project analyzes historical data on electric vehicle registrations and provides a forecast for future registrations. Using time series analysis techniques, including SARIMA and Holt-Winters, this project aims to estimate EV adoption trends based on existing data.

## Project Structure
- **Data Loading and Preprocessing**: Load, clean, and prepare EV registration data for analysis.
- **Exploratory Data Analysis (EDA)**: Visualize key trends, distributions, and geographical insights.
- **Time Series Analysis and Forecasting**: Analyze trends over time and forecast future registrations using SARIMA and other models.

## Features
1. **Data Cleaning**: Handles missing values, duplicates, and filters data by completed years up to 2023.
2. **Exploratory Data Analysis (EDA)**:
   - EV adoption over time
   - Distribution by electric vehicle type, manufacturer, and model
   - Geographical distribution at county and city levels
3. **Time Series Forecasting**:
   - **SARIMA**: Seasonal Autoregressive Integrated Moving Average model to capture seasonality and trends.
   - **Alternative Model**: Holt-Winters Exponential Smoothing as an option if SARIMA or Prophet is unavailable.

## Requirements
Ensure you have the following libraries installed:

```bash
pip install pandas matplotlib seaborn statsmodels
```

--- 

This README covers all main aspects of the project, guiding users through setup, usage, and forecasting steps. Let me know if you’d like additional customization!
