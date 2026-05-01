📌 Bitcoin Market Sentiment vs Trader Performance Analysis
🧠 Objective
This project explores the relationship between Bitcoin market sentiment (Fear vs Greed) and trader performance using historical trading data. The goal is to uncover patterns in trading behavior and derive insights that can improve decision-making and risk management.

📊 Datasets Used
Bitcoin Market Sentiment Dataset

Columns: Date, Classification (Fear/Greed)

Historical Trader Data (Hyperliquid)

Includes: account, symbol, execution price, size, side, time, closedPnL, leverage, etc.

⚙️ Methodology
Data cleaning and preprocessing

Automatic detection and handling of column inconsistencies

Feature engineering (PnL, win rate, sentiment encoding)

Merging datasets on date

Exploratory data analysis and visualization

📈 Key Findings
Traders tend to generate higher average profits during Greed phases

Leverage and trade size increase during Greed, indicating higher risk-taking

Fear phases show lower but more stable returns

Greed phases exhibit higher volatility, indicating a risk-reward tradeoff

🔍 Behavioral Insights
Traders become more aggressive during bullish sentiment

Increased leverage during Greed amplifies both gains and losses

Conservative trading behavior is more common during Fear

Market sentiment strongly influences trading decisions

🧑‍💼 Top Trader Insights
Top-performing traders demonstrate:

Consistent profitability across both sentiment phases

Better risk management practices

Less dependency on emotional market sentiment

🧠 Strategy Recommendations
Adjust leverage based on market sentiment

Avoid excessive risk exposure during Greed phases

Use Fear phases for more stable and controlled trading

Implement adaptive strategies rather than fixed approaches

🛠️ Tech Stack
Python

Pandas

NumPy

Matplotlib

Seaborn

📌 Conclusion
Market sentiment plays a significant role in shaping trader behavior and performance. Incorporating sentiment-aware strategies can help traders optimize returns while managing risk more effectively.
