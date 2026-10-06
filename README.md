# Supply Chain Demand Forecasting Using Transformer Models
##  Project Overview
This project focuses on forecasting future supply chain demand using time-series forecasting techniques. The system compares traditional statistical forecasting with deep learning-based forecasting to improve demand prediction and support better inventory and supply chain planning.

##  Objectives

- Forecast future product demand using historical data.
- Compare traditional ARIMA forecasting with Transformer-based Temporal Fusion Transformer (TFT).
- Improve demand planning and inventory management.
- Evaluate forecasting performance using standard error metrics.
- ## Technologies Used

- Python
- ARIMA
- Temporal Fusion Transformer (TFT)
- Time-Series Forecasting
- Deep Learning
- PyTorch Forecasting
- Pandas
- NumPy
- Matplotlib
- 
- ##  Models Used

 1. ARIMA

ARIMA is used as a traditional statistical baseline model for time-series demand forecasting.

 2. Temporal Fusion Transformer (TFT)

TFT is a deep learning-based forecasting model designed to capture complex temporal patterns and relationships in time-series data.
## Evaluation Metrics

The forecasting models can be evaluated using:

- **MAE** – Mean Absolute Error
- **RMSE** – Root Mean Square Error
- **SMAPE** – Symmetric Mean Absolute Percentage Error
  
- ##  Workflow
text
Historical Supply Chain Data
          ↓
     Data Preprocessing
          ↓
   Time-Series Preparation
          ↓
     ┌───────────────┐
     ↓               ↓
   ARIMA            TFT
     ↓               ↓
     └───────┬───────┘
             ↓
    Forecast Evaluation
             ↓
      Demand Prediction

## Expected Outcome
The project aims to identify the forecasting approach that provides better demand prediction accuracy and can support inventory planning and supply chain decision-making.
