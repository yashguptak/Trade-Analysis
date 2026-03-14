📊 Bitcoin Market Sentiment vs Trader Performance Analysis

This project analyzes the relationship between Bitcoin Market Sentiment (Fear & Greed Index 📉📈) and trader performance using Hyperliquid historical trading data.
The objective is to explore how market psychology influences trader behavior, profitability, trade size, and trading decisions. By combining sentiment data with real trading records, the project uncovers patterns that can help in developing data-driven trading insights.

📁 Datasets
1️⃣ Bitcoin Market Sentiment Dataset

Contains daily Fear & Greed Index values representing overall crypto market sentiment.

Sentiment categories include:

Extreme Fear 😨

Fear 😟

Neutral 😐

Greed 😃

Columns:

Timestamp

Value

Classification

Date

2️⃣ Hyperliquid Historical Trading Data

Contains detailed trade records including execution information and trader performance.

Important columns:

Account

Coin

Execution Price

Size Tokens

Size USD

Side (Buy/Sell)

Timestamp IST

Direction

Closed PnL

Fee

Trade ID

⚙️ Project Workflow

1️⃣ Data Cleaning and Preprocessing
2️⃣ Timestamp Conversion and Normalization
3️⃣ Merging Trading Data with Sentiment Data
4️⃣ Exploratory Data Analysis (EDA)
5️⃣ Sentiment-Based Trading Behavior Analysis
6️⃣ Visualization and Insight Generation

📊 Key Analyses

The project explores multiple analytical perspectives:

📈 Profit Analysis

Compare average trader profit under different sentiment conditions.

📉 Trade Volume Analysis

Evaluate how trading activity changes during Fear vs Greed markets.

🔄 Buy vs Sell Behavior

Analyze trader decision patterns across market sentiment.

🔗 Correlation Analysis

Study relationships between:

Trade Size

Fees

Profit/Loss

🏆 Trader Performance

Identify top-performing traders and overall profitability trends.

📊 Visualizations

The project includes several visual analytics:

📊 Correlation Heatmaps

📈 Plotly Interactive Charts

🥧 Pie Charts for Buy/Sell Distribution

📉 Profit vs Market Sentiment

📊 Trade Volume Comparisons

These visualizations help uncover hidden patterns in trader behavior.

🛠 Technologies Used

Python 🐍

Pandas

NumPy

Matplotlib

Seaborn

Plotly

🔍 Key Insights

Some insights discovered from the analysis:

Trading activity tends to increase during Fear and Extreme Fear markets, indicating panic trading.

Greed sentiment periods show higher average profits, reflecting bullish momentum.

Buy trades dominate during Greed markets, while sell pressure increases during Fear markets.

Larger trade sizes often lead to greater profit volatility.

📂 Project Structure
bitcoin-sentiment-analysis
│
├── data
│   ├── historical_data.csv
│   ├── fear_greed_index.csv
│
├── notebooks
│   ├── analysis.ipynb
│
├── images
│   ├── charts
│
├── README.md
🚀 Project Goal

The main goal of this project is to understand how market sentiment impacts trader performance and behavior in cryptocurrency markets. The findings can help traders and analysts design more informed and sentiment-aware trading strategies.
