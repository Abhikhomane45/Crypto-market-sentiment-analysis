# Crypto-market-sentiment-analysis

---

# 📊 Fear & Greed Trading Analysis

## 📌 Project Overview

This project analyzes the impact of **market sentiment (Fear, Neutral, and Greed)** on **trading performance** using historical trading data from the Hyperliquid platform combined with the **Crypto Fear & Greed Index**.
The goal is to understand how sentiment influences **profitability, win rate, and risk-taking behavior**.

---

## 🎯 Objectives

* Analyze trading **profitability** under different market sentiments
* Compare **win rates** across Fear, Neutral, and Greed conditions
* Study **risk behavior** using trade size
* Identify **behavioral patterns** of traders
* Evaluate whether **contrarian strategies** perform better

---

## 📂 Datasets Used

### 1. Hyperliquid Historical Trade Data

* Trade executions with price, size, direction, fees, and realized PnL
* Total records: **211,224**

### 2. Crypto Fear & Greed Index

* Daily market sentiment scores
* Categorized into: Fear, Neutral, Greed

---

## 🧹 Data Cleaning & Preparation

* Checked and confirmed **no missing values**
* Converted timestamps to standard datetime format
* Aggregated executions to **order-level trades**
* Filtered **closed trades only**
* Calculated **fee-adjusted Net PnL**
* Normalized sentiment labels into Fear, Neutral, and Greed

---

## ⚙️ Methodology

* **Aggregation level:** Order-level analysis
* **Metrics calculated:**

  * Net PnL
  * Win Rate
  * Trade Size (USD)
* **Grouping strategy:** By market sentiment
* **Visualization techniques:**

  * Bar charts (PnL, trade size)
  * Count plots (win vs loss)
  * Box plots (PnL distribution)

---

## 📈 Key Insights

* Fear sentiment yields the **highest profitability**
* Traders allocate **more capital during Fear**
* Greed sentiment reduces **win consistency**
* Higher volatility during Fear leads to **better risk-adjusted returns**

---

## 🧠 Conclusion

The analysis shows that **market sentiment strongly influences trading outcomes**. Trades executed during Fear conditions outperform Greed conditions in terms of profitability, consistency, and capital deployment. These results support the effectiveness of **contrarian, sentiment-aware trading strategies** in volatile cryptocurrency markets.

---

## 🛠️ Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📁 Project Structure

```
fear-greed-trading-analysis/
│
├── dataset/
│   ├── historical_data.csv
│   └── fear_greed_index.csv
│
├── Assesment.ipynb
├── README.md
```



## 👤 Author

**Abhijeet Khomane**

---





