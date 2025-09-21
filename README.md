# Stock Market Movement Prediction  

## 📌 Overview  
This project predicts whether the **S&P 500 index** will go **up (Bull) or down (Bear)** the next day using machine learning.  
We compare two models:  

- **Logistic Regression** → baseline classifier.  
- **Random Forest Classifier** → ensemble method for better accuracy.  

The notebook also includes a **backtesting framework** that simulates model performance across historical data.  

---

## 📊 Key Findings  
- Logistic Regression provides a simple benchmark.  
- Random Forest consistently achieves better **precision** and captures market patterns more effectively.  

Example results:  

Logistic Regression Precision: 0.51
Random Forest Precision: 0.57


Visualizations show Random Forest predictions align better with actual trends.

## ⚙️ Installation

Clone this repository and install dependencies:

git clone https://github.com/HariharanJ2002/stock-price-prediction.git
cd stock-price-prediction
pip install -r requirements.txt

## 🚀 Usage

Run the Jupyter Notebook:

jupyter notebook Stock_Price_Prediction_Clean.ipynb


Steps inside the notebook:

Download historical S&P 500 data with Yahoo Finance (yfinance).

Preprocess data (create target variable: up or down).

Train Logistic Regression and Random Forest.

Compare performance using precision score and plots.

## 📈 Visualizations

The notebook generates side-by-side plots of Actual vs Predicted values:

Logistic Regression: baseline model.

Random Forest: better accuracy and trend capture.

## 🔮 Future Improvements

Add technical indicators (moving averages, RSI, MACD).

Try deep learning models (LSTMs, GRUs).

Apply to individual stocks (AAPL, TSLA, etc.).

Deploy as a simple web app using Streamlit/Flask.

📂 Project Structure
├── Stock_Price_Prediction_Clean.ipynb   # Main notebook with code & analysis
├── requirements.txt                     # Dependencies
└── README.md                            # Project documentation

## 🏷️ Tags

Machine Learning · Finance · Stock Market · Time Series · Data Science
