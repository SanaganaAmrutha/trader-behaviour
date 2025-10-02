# trader-behaviour
Trader Behavior Insights: Linking Fear & Greed Sentiment with Trading Performance
*  Project Overview

This project explores the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance (Hyperliquid trading data).
The goal was to uncover patterns in how traders behave under different sentiment conditions and extract actionable insights that can support smarter trading strategies.

I combined two datasets:

Fear & Greed Index (sentiment classification + intensity)

Historical Hyperliquid Trader Data (accounts, trades, PnL, leverage, etc.)

Through data preprocessing, exploratory analysis, statistical testing, and visualizations, I identified patterns in profitability, risk-taking, and trader behavior.

* Key Insights

Profitability drops ~36% during Fear periods compared to Greed periods (avg PnL: 50 vs 78).

Trading activity is 68% lower in Greed phases than in Fear phases — traders trade more in fearful conditions, even though average outcomes are worse.

Contrarian strategies exist: ~30 accounts consistently profit in Fear periods while most traders lose.

Risk exposure rises in Greed phases, suggesting traders increase leverage during positive sentiment.

Coin-level differences: certain assets show stronger sentiment-driven volatility, meaning strategy design should adapt per coin.

* Repository Structure

notebook.ipynb → Full Jupyter Notebook with data preprocessing, EDA, and analysis

summary.pdf → One-page report with actionable insights and charts

figures/ → Saved plots (heatmaps, boxplots, daily PnL trends)

* Methods Used

Data Cleaning & Merging (timestamp parsing, aligning sentiment with trades)

EDA & Visualization (Seaborn, Matplotlib heatmaps, boxplots, time series)

Statistical Testing (t-tests & Mann-Whitney U for PnL differences)

Trader-Level Aggregation (per-account win rate, average PnL, volume)

Actionable Insights Extraction (turning analysis into strategy recommendations)

* How to Run

1. Clone this repository.
2. Download the datasets from the provided Google Drive links.
3. Open `Trader_Insights.ipynb` in Jupyter Notebook.
4. Run all cells sequentially to reproduce analysis, visualizations, and insights.
