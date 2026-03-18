# Bitcoin-Trader-Behavior-Insights
Data Science Analysis exploring the relationship between Market Sentiment and Trader Performance.

## Assignment Overview
This project explores the relationship between Bitcoin market sentiment (Fear & Greed Index) and historical trader performance data from Hyperliquid. The objective is to uncover hidden patterns that can drive smarter, more profitable trading strategies.

## Key Insights
Contrarian Opportunity: Average PnL is often highest during periods of Extreme Fear, validating the "buy the dip" strategy.
Volume vs. Profitability: While trading volume peaks during Greed (indicating FOMO), profitability tends to be lower compared to fearful markets.
Top Trader Behavior: The most profitable accounts consistently execute trades during negative sentiment phases.

##📊 Visualizations & Analysis
1. Average Trader PnL by Sentiment
This chart shows which market sentiment yields the highest average profit per trade.Average PnL by Sentiment

Analysis: Traders generate an average profit of $121.90 during Extreme Fear, compared to $121.90 during Extreme Greed. This suggests entering the market when others are fearful leads to better returns.

2. Win Rate by Sentiment
This chart shows the percentage of trades that closed in profit.Win Rate by Sentiment

Analysis: The win rate remains consistent across sentiments at approximately 51.06%, but the magnitude of wins is greater in Fear markets.

3. Trading Volume Distribution
This chart shows where traders are most active.Volume by Sentiment

Analysis: Total volume is highest during Greed. This indicates that retail traders tend to chase rallies, often entering late and missing the optimal entry points found in Fear markets.

##💡 Strategic Recommendations
Based on the analysis, here are three actionable strategies for PrimeTrade.ai:

Sentiment-Based Alerts: Implement a "High Opportunity" alert when the Fear & Greed Index drops below 25 (Extreme Fear), prompting users to consider long positions.
Risk Mitigation: Automatically reduce allowable leverage for users trading during "Extreme Greed" to protect capital from potential corrections.
Smart Leaderboards: Highlight traders who profit consistently during Fear periods in the Copy Trading section, as they likely possess superior risk management skills.

##🛠️ Tech Stack & Code
Python: Primary language for data analysis.
Pandas: Used for data cleaning, merging, and manipulation.
Matplotlib / Seaborn: Used for data visualization.
Google Colab: Development environment.
