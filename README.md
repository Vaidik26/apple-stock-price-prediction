# 🍏 Apple Stock Price Predictor using LSTM

Predict future Apple Inc. (AAPL) stock prices using historical data and a Long Short-Term Memory (LSTM) neural network.


## 📌 Overview

This project leverages a Recurrent Neural Network (RNN) with LSTM layers to forecast future stock prices based on historical AAPL data. It includes data preprocessing, model training, evaluation, and visualization of results.


## 🧠 Tech Stack

Programming Language: Python

Libraries:

pandas, numpy for data manipulation

matplotlib, seaborn for visualization

scikit-learn for preprocessing

TensorFlow / Keras for deep learning (LSTM)


## 🔄 Workflow

Load and preprocess data: Clean, normalize and create time-series sequences.

Split data: Train-test split (usually 70:30).

Model: Define and compile an LSTM model.

Train: Fit model on training data.

Evaluate: Visualize performance with actual vs predicted prices.

Save: Trained model for future inference.


## 📊 Results

![Predicted vs Actual](C:/Workspace/Projects/Stock price prediction/artifacts/Predicted vs Real Stock price.png)

![Predicted vs Actual for last 100 stocks](C:/Workspace/Projects/Stock price prediction/artifacts/Predicted vs Real Stock price for 100 newest stock.png)


## 📦 Dataset

Source: [Yahoo Finance](https://finance.yahoo.com/quote/AAPL/history/?p=AAPL)

Columns used: Date, Open, High, Low, Close, Volume


## 📌 Future Work

Integrate technical indicators (MACD, RSI, etc.)

Use multivariate LSTM (add external features)

Deploy as a web app using Streamlit or Flask


## 🙌 Author

Vaidik Yadav

📧 vaidiky90@gmail.com

🌐 LinkedIn : https://www.linkedin.com/in/vaidik-yadav-260a60248/

