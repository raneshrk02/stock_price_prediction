# Stock Price Prediction with Sentiment Analysis

This project leverages machine learning and sentiment analysis to forecast stock price movements. It integrates financial news headlines and historical stock data to improve prediction accuracy using a hybrid approach.

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/stock-price-prediction.git
cd stock-price-prediction
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

* `Stock_Price_prediction.ipynb` – Contains the full pipeline: data collection, preprocessing, sentiment extraction, model training, and prediction.

---

## Features

* Uses historical stock data from Yahoo Finance.
* Extracts sentiment scores from financial news using VADER.
* Combines numerical and textual inputs for a better stock prediction model.
* Implements LSTM Fully Connected Neural Network architecture
* Visualizes predictions and trends for better analysis.

---

## Future Work

* Deploy a real-time dashboard for stock monitoring.
* Add Twitter sentiment integration via Tweepy API.