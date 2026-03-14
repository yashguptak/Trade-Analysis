# 📊 Bitcoin Market Sentiment vs Trader Performance Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Visualization](https://img.shields.io/badge/Visualization-Plotly%20%7C%20Seaborn-orange)

This project analyzes the relationship between **Bitcoin Market Sentiment (Fear & Greed Index 📉📈)** and **trader performance using Hyperliquid historical trading data**.

The goal is to understand how **market sentiment affects trading behavior, profitability, trade volume, and risk-taking decisions**.

---

## 📁 Datasets

### 1️⃣ Bitcoin Market Sentiment Dataset
Contains daily **Fear & Greed Index values** and sentiment classification.

Sentiment categories:
- Extreme Fear 😨
- Fear 😟
- Neutral 😐
- Greed 😃

Columns include:
- Timestamp
- Value
- Classification
- Date

---

### 2️⃣ Hyperliquid Historical Trading Data

Contains detailed trading records.

Important columns:
- Account
- Coin
- Execution Price
- Size Tokens
- Size USD
- Side (BUY / SELL)
- Timestamp IST
- Direction
- Closed PnL
- Fee
- Trade ID

---

## ⚙️ Project Workflow

1. Data Cleaning and Preprocessing  
2. Timestamp Conversion and Normalization  
3. Merging Trading Data with Sentiment Data  
4. Exploratory Data Analysis (EDA)  
5. Sentiment-Based Trading Behavior Analysis  
6. Visualization and Insight Generation  

---

## 📊 Analysis Performed

- Profit analysis by market sentiment
- Trade volume analysis
- Buy vs Sell behavior
- Correlation analysis between trade size, fees, and profit
- Top trader performance analysis

---

## 📊 Visualizations

- 📊 Correlation Heatmaps
- 📈 Plotly Interactive Charts
- 🥧 Pie Charts for Buy/Sell Distribution
- 📉 Profit vs Sentiment Analysis

---

## 🛠 Technologies Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

---

## 🔍 Key Insights

- Trading activity increases during **Fear market conditions**.
- **Greed sentiment periods show higher average profitability**.
- Buy trades dominate during **bullish sentiment**, while sell pressure increases during fearful markets.
- Larger trades lead to **higher profit volatility**.

---
Note: The original dataset is large and exceeds GitHub’s file size limits. 
A sampled dataset is provided for demonstration and reproducibility.
⭐ If you like this project, feel free to **star the repository**.
