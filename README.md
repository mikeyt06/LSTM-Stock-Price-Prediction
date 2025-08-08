# 📈 LSTM Stock Price Prediction

A simple **LSTM neural network** to predict stock closing prices using historical data from Yahoo Finance.

**Tech:** Python, TensorFlow/Keras, Pandas, NumPy, scikit-learn, Matplotlib, yfinance  
**Ticker used:** DAC (2015–2025)  
**Lookback window:** 100 days  

---

## 📊 Sample Output
Test Loss: ~0.00126  

![Predictions](assets/predictions.png)

---

## ▶️ Run

**Colab:**  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/<your-username>/LSTM-Stock-Price-Prediction/blob/main/LSTM_Stock_Prediction.ipynb)

**Local:**
```bash
git clone https://github.com/<your-username>/LSTM-Stock-Price-Prediction.git
cd LSTM-Stock-Price-Prediction
pip install -r requirements.txt
jupyter notebook LSTM_Stock_Prediction.ipynb
