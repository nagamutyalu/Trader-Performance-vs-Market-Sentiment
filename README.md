# Trader Performance vs Market Sentiment Analysis

## Objective
This project analyzes how Bitcoin market sentiment (Fear/Greed Index) influences trader behavior and profitability on Hyperliquid.

## Datasets Used
1. Historical Trader Data (Hyperliquid)
2. Bitcoin Fear & Greed Index Dataset

## Methodology
- Cleaned and aligned historical trade data with daily sentiment data.
- Created performance metrics: daily PnL, win rate, trade frequency, and average trade size.
- Compared trader behavior across Fear and Greed regimes.
- Segmented traders based on activity and profit volatility.
- Applied statistical testing to validate findings.

## Key Insights
- Trade size and activity increase during Greed periods.
- PnL volatility increases during Extreme Fear.
- Frequent traders perform better in bullish markets but struggle during uncertainty.

## Strategy Recommendations
- Adjust position size dynamically based on sentiment.
- Reduce trading activity during Fear regimes.
- Activate high-frequency strategies selectively during Greed markets.

## How to Run
Install required libraries:
pip install pandas numpy matplotlib seaborn scikit-learn scipy
Open the Jupyter Notebook and run all cells sequentially.
