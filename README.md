# Trader Behavior and Market Sentiment Analysis

## Project Overview

This project analyzes the relationship between trader performance on the Hyperliquid platform and the broader Bitcoin market sentiment, as measured by the Fear & Greed Index. The goal is to uncover hidden patterns in trader behavior and provide data-driven insights that could lead to smarter trading strategies.

This project was completed as part of a data science assignment for a Junior Data Scientist role.

## Datasets

*   **`fear_greed_index.csv`**: Daily data for the Crypto Fear & Greed Index.
*   **`historical_data.csv`**: A dataset of historical trades from Hyperliquid, including columns like account, coin, PnL, and side.

## Key Findings

1.  **Strong Correlation:** There is a clear positive correlation between market sentiment and average trader performance. Win rates and PnL are highest during periods of 'Greed' and lowest during 'Extreme Fear'.
2.  **Contrarian Behavior:** Traders exhibit a tendency to buy during 'Extreme Fear' (buying the dip) and sell during 'Extreme Greed' (selling the top).
3.  **Elite Trader Differentiation:** Top-performing traders are distinguished by their ability to maintain better performance during neutral and fearful market conditions, not just by capitalizing on greedy markets.
4.  **Asset Sensitivity:** The impact of sentiment varies by asset, with more speculative tokens like `HYPE` showing a more pronounced correlation.

## How to Run

1.  Clone this repository.
2.  Ensure you have Python installed with the following libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`.
3.  Open and run the `Primetrade (1).ipynb` notebook in a Jupyter environment. The notebook is self-contained and will load the included CSV files.
