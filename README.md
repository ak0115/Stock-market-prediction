# Stock-market-prediction
This project is a Stock Market Prediction System that uses deep learning to forecast stock prices based on historical data. Built using LSTM (Long Short-Term Memory) networks, the app provides a user-friendly Streamlit interface where users can input stock symbols and visualize actual vs. predicted prices.

Features
Fetches historical stock data using yFinance

Predicts future stock prices using a trained LSTM model

📈 Interactive visualizations:

Actual Price vs Moving Averages (50, 100, 200 days)

Original vs Predicted stock price comparison

Deployed using Streamlit for real-time interaction

🧠 Model Details
Model trained on closing prices of stocks

Preprocessing includes normalization using MinMaxScaler

Uses a sliding window of 100 days to predict future prices

Model saved as .keras file and loaded for inference
