Bitcoin Market Sentiment vs Trader Performance Analysis

🔍 Project Overview
This project analyzes the relationship between Bitcoin market sentiment (Fear/Greed Index) and trader performance using historical trading data. 
The objective is to identify patterns in trading behavior and evaluate how market emotions influence profitability and risk-taking decisions.

🎯 Objectives
Examine how market sentiment impacts trading outcomes
Identify patterns in profitability during Fear vs Greed phases
Analyze trader behavior (buy/sell decisions, trade size)
Build a machine learning model to predict trade success

📁 Datasets Used
1. Market Sentiment Dataset
Features: Date, Classification (Fear/Greed)
Represents overall market psychology
2. Historical Trader Dataset
Features include:
execution price, size usd, side, closed pnl
timestamp, coin, and other trade-related attributes
Captures detailed trader activity and outcomes

⚙️ Methodology
🔹 Data Preprocessing
Cleaned and formatted timestamps
Merged datasets on date to align trades with sentiment
Removed irrelevant features
Converted categorical variables using one-hot encoding
🔹 Exploratory Data Analysis (EDA)
Compared average profit across Fear and Greed phases
Evaluated win rate (profitable trades)
Analyzed trade size as a proxy for risk
Studied buy vs sell behavior under different sentiments
🔹 Machine Learning Model
Applied Logistic Regression for classification
Target variable:
Profit/Loss derived from closed pnl
Features used:
Trade size (size usd)
Trade direction (side)
Market sentiment (classification)

📈 Results
The model achieved an accuracy of approximately 75%
Market sentiment showed a noticeable influence on trading outcomes
Traders exhibited different behavior patterns during Fear and Greed phases
Larger trade sizes were associated with higher risk and variability in outcomes

🧠 Key Insights
Greed phases tend to show higher trading activity and risk-taking
Fear phases often result in more cautious behavior
Trade size significantly impacts profitability
Market sentiment can be used as a useful predictive signal

🚀 Conclusion
This project demonstrates that market psychology plays a crucial role in trading performance. By combining sentiment data with trading activity, meaningful insights 
can be derived to support data-driven trading strategies. The machine learning model further validates that trade outcomes can be reasonably predicted using a 
combination of behavioral and market indicators.

🛠️ Tools & Technologies
Python
Pandas
Matplotlib
Scikit-learn
