# Market Sentiment vs Trader Behavior Analysis (Hyperliquid)

## Overview
This project analyzes how Bitcoin market sentiment (Fear vs Greed) influences trader behavior and performance on Hyperliquid.

The goal is to identify patterns in trading activity, profitability, and risk-taking behavior, and derive actionable strategies.

---

## Data Access

Due to file size limitations, the datasets are not included in this repository.

Please download them from the following link:

Market_Sentiment_Datasets : [https://drive.google.com/drive/folders/1SbkSVLJOCkeihbhgskrThESu9bB_Ae1T?usp=sharing]

After downloading, upload the CSV files when running the notebook.

--- 

## Methodology

- Loaded and inspected both datasets (sentiment + trading data)
- Cleaned data (checked for missing values and duplicates)
- Converted timestamps to daily format for alignment
- Merged datasets on date
- Created key metrics:
  - Daily PnL per account
  - Win rate
  - Trade frequency
  - Trade size (used as proxy for risk)

---

## Key Insights

- Trading activity is highest during Fear and Greed periods, indicating sentiment-driven participation
- Higher activity does not necessarily lead to higher profitability
- Traders take larger positions during Fear, increasing risk exposure
- Win rates are higher during Greed phases, suggesting better performance in trending markets
- Overall behavior is influenced more by sentiment than disciplined strategy

---

## Strategy Recommendations

- Reduce trading activity during Fear periods to avoid reactive decisions
- Limit position sizes during volatile conditions
- Avoid overconfidence during Greed phases despite higher win rates
- Focus on disciplined and consistent trading rather than sentiment-driven actions

---

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook
2. Upload the dataset CSV files when prompted
3. Run all cells sequentially to reproduce results

📊 The full analysis, charts, and insights are available in the notebook.
---

## Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Google Colab
