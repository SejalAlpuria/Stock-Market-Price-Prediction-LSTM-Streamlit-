# Stock-Market-Price-Prediction-LSTM-Streamlit-
Stock Market Price Prediction using LSTM and Streamlit | Deep learning-based model to forecast stock prices with an interactive dashboard
📈 Stock Market Price Prediction (LSTM + Streamlit)
📌 Overview

This project implements a Stock Market Price Prediction model using Long Short-Term Memory (LSTM) deep learning.
The model predicts future stock closing prices and provides an interactive Streamlit dashboard for visualization.

🛠️ Tools & Technologies Used

Python 🐍

TensorFlow / Keras (LSTM Model)

Pandas & NumPy (Data processing)

Matplotlib & Seaborn (Visualization)

Streamlit (Interactive UI)

📊 Features

Load stock market data (Yahoo Finance / CSV Upload 📂)

Train LSTM model on historical data 📈

Predict future stock prices 🔮

Interactive dashboard with:

Date range selection 📅

Actual vs Predicted comparison charts 📊

Download option for predictions ⬇️

📂 Project Structure
Stock_Market_Prediction/
│── data/                 # Dataset (CSV or downloaded from Yahoo Finance)
│── model/                # Saved LSTM model files
│── app.py                # Streamlit dashboard code
│── stock_prediction.ipynb # Jupyter Notebook (model training)
│── requirements.txt      # Dependencies
│── README.md             # Project documentation

📥 How to Use

Clone this repository:

git clone https://github.com/SejalAlpuria/Stock_Market_Prediction.git
cd Stock_Market_Prediction


Install dependencies:

pip install -r requirements.txt


Run the Streamlit app:

streamlit run app.py

📊 Dashboard Preview

