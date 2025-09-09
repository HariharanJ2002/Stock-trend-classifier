# Stock-trend-classifier
Machine learning project that predicts S&amp;P 500 stock index movements (up or down) using historical data. Includes Logistic Regression vs Random Forest comparison, backtesting, and visualizations.
📘 Stock Price Movement Prediction (S&P 500)
📌 Overview

This project predicts whether the S&P 500 index will go up or down tomorrow using machine learning.
We use historical data from Yahoo Finance and compare two models:

Logistic Regression → baseline model.

Random Forest Classifier → ensemble model.

The notebook also includes a backtesting framework to simulate how models would perform over time.

📊 Results

Logistic Regression provides a simple baseline but struggles with complex patterns.

Random Forest achieves higher precision and follows market movements more closely.

Example precision scores:

Logistic Regression Precision: 0.51
Random Forest Precision: 0.57


Visualizations show Random Forest predictions align better with actual trends.

⚙️ Installation

Clone this repository and install dependencies:

git clone https://github.com/your-username/stock-price-prediction.git
cd stock-price-prediction
pip install -r requirements.txt

🚀 Usage

Run the Jupyter Notebook:

jupyter notebook Stock_Price_Prediction_Clean.ipynb


Steps inside the notebook:

Download historical S&P 500 data with Yahoo Finance (yfinance).

Preprocess data (create target variable: up or down).

Train Logistic Regression and Random Forest.

Compare performance using precision score and plots.

📈 Visualizations

The notebook generates side-by-side plots of Actual vs Predicted values:

Logistic Regression: baseline model.

Random Forest: better accuracy and trend capture.

🔮 Future Improvements

Add technical indicators (moving averages, RSI, MACD).

Try deep learning models (LSTMs, GRUs).

Apply to individual stocks (AAPL, TSLA, etc.).

Deploy as a simple web app using Streamlit/Flask.

📂 Project Structure
├── Stock_Price_Prediction_Clean.ipynb   # Main notebook with code & analysis
├── requirements.txt                     # Dependencies
└── README.md                            # Project documentation

🏷️ Tags

Machine Learning · Finance · Stock Market · Time Series · Data Science
