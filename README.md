# AI-Based Financial Time Series Forecasting using LSTM

## Overview

This project implements a Long Short-Term Memory (LSTM) neural network to forecast stock prices using historical financial data. The model learns temporal patterns from past stock prices and predicts future values through time-series analysis.

The project covers the complete forecasting pipeline, including data preprocessing, sequence generation, model training, prediction, performance evaluation, and visualization.

---

## Project Structure

```
AI-Based-Financial-Time-Series-Forecasting/
│
├── src/
│   └── reliance_lstm_time_series.py
│
├── dataset/
│   └── reliance_stock_sample.csv
│
├── screenshots/
│   ├── actual_vs_predicted_detailed.png
│   └── training_loss_detailed.png
│
├── README.md
└── requirements.txt
```

---

## Workflow

1. Load and preprocess stock market data.
2. Convert date values and sort records.
3. Extract closing prices.
4. Apply Min-Max normalization.
5. Generate time-series sequences.
6. Reshape data for LSTM input.
7. Build and train the LSTM model.
8. Predict stock prices on test data.
9. Evaluate model performance using error metrics.
10. Visualize prediction results.
11. Forecast the next day's stock price.

---

## Model Architecture

- LSTM Layer (50 Units)
- Dropout Layer (20%)
- LSTM Layer (50 Units)
- Dropout Layer (20%)
- Dense Layer (25 Units)
- Output Dense Layer (1 Unit)

---

## Evaluation Metrics

The model performance is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## Generated Outputs

After execution, the project generates:

- Actual vs Predicted Stock Price Graph
- Training Loss Graph
- Next-Day Stock Price Prediction
- Prediction Output CSV File
- Trained LSTM Model File

---
