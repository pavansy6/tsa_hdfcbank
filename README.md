# 📈 Time Series Analysis of HDFCBANK Stock

This project explores the **historical stock prices of HDFC Bank (HDFCBANK.NS)** using **time series analysis** and the **ARIMA model**. The analysis includes exploratory visualization, model training, evaluation, and forecasting of future stock trends.

---

## 🔍 Project Overview
- Downloaded historical stock price data of **HDFC Bank** from *Yahoo Finance* using `yfinance`.
- Focused on the **closing price** (`Close`) for analysis.
- Split the dataset into **train (80%)** and **test (20%)** sets.
- Trained an **ARIMA (5,1,1)** model to capture stock price trends.
- Evaluated model performance using **RMSE (Root Mean Squared Error)**.
- Forecasted stock prices for the **test period** and **future values**.
- Visualized train, test, predictions, and future forecasts with confidence intervals.

---

## 🛠️ Tools & Libraries
- Python 🐍  
- Pandas  
- Numpy  
- Matplotlib  
- Statsmodels (ARIMA)  
- scikit-learn (metrics)  
- yfinance  

---

## 📊 Methodology
1. **Data Collection**  
   - Used `yfinance` to fetch HDFCBANK stock prices (`1995-11-08` to `2025-09-10`).  

2. **Preprocessing**  
   - Extracted the `Close` column.  
   - Renamed it to `Price`.  

3. **Evaluation**  
   - Calculated **RMSE** for test predictions.

4. **Residual Analysis**
   - Outlier detection and removal
   - Residual Plotting

---

## 📈 Results
- The ARIMA model captures the **overall upward trend** of HDFCBANK stock prices.  
- The test predictions align closely with the actual data.  
- Future forecasts provide an outlook with **confidence intervals**, highlighting uncertainty in stock movement.  

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/hdfcbank-time-series.git
   cd hdfcbank-time-series
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "Time Series Analysis of HDFCBANK stock by Pavan.ipynb"
   ```

---

## 📌 Next Steps
- Try **different ARIMA orders (p,d,q)** or automated selection (`auto_arima`).  
- Compare ARIMA with other models (SARIMA, Prophet, LSTM).  
- Add trading signals or backtesting strategy.  

---

## 👨‍💻 Author
**Pavan Yadav**  
Passionate about **Data Science, Quant Finance, and AI**.  
