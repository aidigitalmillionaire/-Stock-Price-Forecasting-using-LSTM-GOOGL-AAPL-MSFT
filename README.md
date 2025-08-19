# Stock-Price-Forecasting-using-LSTM-GOOGL-AAPL-MSFT 🚀🔥


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1kIbKb8Ie4_QprZlNFakgxMrpQkF6uQuK?usp=sharing)

This project implements **Stock Price Forecasting** using **Long Short-Term Memory (LSTM) neural networks**.  
The models are trained on **historical stock prices** of **Google (GOOGL), Apple (AAPL), and Microsoft (MSFT)** to predict future closing prices.  
Built and tested in **Google Colab** for reproducibility.

👉 **Detailed Description:** [docs/DESCRIPTION.md](docs/DESCRIPTION.md)

---

## 🔑 Key Features
- Clean and reproducible Colab notebook
- Fetches historical stock data using **yfinance**
- Preprocessing: normalization, windowed time series creation
- Deep Learning: LSTM model for stock price forecasting
- Evaluation: RMSE, MAE, and visualization of predicted vs actual prices
- Forecasting on **GOOGL, AAPL, MSFT**
- Ready-to-run on **Google Colab**

---

## 📂 Project Structure

stock-price-forecasting/

├─ notebook/

│ └─ stock_price_forecasting.ipynb

├─ docs/

│ └─ DESCRIPTION.md

├─ README.md

├─ requirements.txt

└─ .gitignore


---

## 📊 Dataset
- Data Source: [World Stock Prices ( Daily Updating)](World Stock Prices ( Daily Updating )) via the Kaggle Dataset
- Stocks used:
  - **Google (GOOGL)**
  - **Apple (AAPL)**
  - **Microsoft (MSFT)**
- Time period: 2010–2024 (configurable in notebook)

---

## ⚡ How to Run

1. Open notebook in Google Colab:  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1kIbKb8Ie4_QprZlNFakgxMrpQkF6uQuK?usp=sharing)

2. Install dependencies (if running locally):
   ```bash
   pip install -r requirements.txt


   
---

# 3️⃣ docs/DESCRIPTION.md

# Project Description — Stock Price Forecasting using LSTM 📈

This project demonstrates **time series forecasting** for stock prices using **LSTM neural networks**.  
It focuses on three major technology companies: **Google (GOOGL)**, **Apple (AAPL)**, and **Microsoft (MSFT)**.  

# 🔎 Workflow
1. Data Collection
   - Stock data is retrieved from Yahoo Finance using `yfinance`.

2. Preprocessing
   - Close price selected as the target variable.
   - Data normalized using MinMaxScaler.
   - Windowed time series dataset creation for supervised learning.

3. Modeling
   - Long Short-Term Memory (LSTM) network built with TensorFlow/Keras.
   - Configurable hyperparameters (sequence length, batch size, epochs).

4. Evaluation
   - Metrics: RMSE, MAE
   - Visualization: Predicted vs Actual stock prices.

5. Forecasting
   - Short-term predictions on unseen data.
   - Separate models for **GOOGL, AAPL, MSFT**.

---

# 🎯 Applications
- Algorithmic trading & strategy backtesting
- Stock market trend analysis
- Predictive analytics for finance
- Educational deep learning project

---

# 📌 Why LSTM?
Traditional regression models fail to capture sequential dependencies in stock price data.  
**LSTMs** are designed to remember long-term dependencies, making them effective for financial time series forecasting.

numpy
pandas
matplotlib
seaborn
scikit-learn
tensorflow
keras

# ✅ Now your Stock Price Forecasting with LSTM repo will be professional and portfolio-ready with:

Notebook (Colab-friendly)

README (overview + Colab badge)

DESCRIPTION.md (detailed explanation)

