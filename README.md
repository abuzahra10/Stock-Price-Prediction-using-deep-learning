# 📈 Stock Price Prediction using LSTM

This project employs a Long Short-Term Memory (LSTM) neural network to predict stock closing prices based on historical stock market data from Egypt’s EGX indices. Developed as part of the **Advanced Machine Learning - Spring 2025** course at the German International University in collaboration with **Cairo Finance Holding Company (CFH)**.

## 🚀 Project Overview

Egypt's stock market (EGX) is characterized by volatility influenced by economic and regional dynamics. This project aims to harness the power of deep learning—specifically LSTM networks—to capture temporal dependencies and forecast future stock prices with improved accuracy.

## 🧠 Model Used

We used an **LSTM (Long Short-Term Memory)** network, well-suited for time-series prediction due to its ability to learn long-term dependencies in sequential data. The model was trained to predict the `Close` price based on features like:

- `Open`
- `High`
- `Low`
- `Volume`
- `Price`

## 📊 Dataset

The dataset includes daily stock data with the following key columns:

| Column | Description                |
|--------|----------------------------|
| Date   | Trading day (YYYY-MM-DD)   |
| Open   | Opening price              |
| High   | Highest price of the day   |
| Low    | Lowest price of the day    |
| Close  | Closing price              |
| Price  | Final closing price        |
| Volume | Shares traded              |

> Data was preprocessed and scaled before feeding into the model.

## 📁 Structure

```bash
Stock-Price-Prediction-using-deep-learning/
├── data/
│   └── stock_data.csv
├── models/
│   └── lstm_model.h5
├── notebook/
│   └── stock_price_prediction_lstm.ipynb
├── README.md
└── requirements.txt
