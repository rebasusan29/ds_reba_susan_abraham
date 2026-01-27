# Trader Behavior & Market Sentiment Analysis

## Overview
This repository contains the analysis for the PrimeTrade AI Data Science task. It explores the relationship between trader performance (PnL, Volume) and market sentiment (Fear & Greed Index) to identify behavioral inefficiencies.

**Google Colab Link:** [INSERT YOUR GOOGLE COLAB LINK HERE]

## Key Findings
- **Euphoria Trap:** Trader profitability peaks during "Greed" ($87.89) but drops by **~71%** when sentiment shifts to "Extreme Greed" ($25.42).
- **High Activity in Fear:** **72%** of all recorded trades occurred during "Fear" periods, driven by high-volume volatility.

## Files
- `notebook_1.ipynb`: Data cleaning, merging, and analysis code.
- `ds_report.pdf`: Executive summary and detailed strategic insights.
- `csv_files/`: Contains the raw and processed datasets.
- `outputs/`: Generated visualizations of PnL, Volume, and Activity.

## Note on Data
The assignment instructions referenced a `Leverage` column, but it was not present in the provided `historical_data.csv`. The analysis was adjusted to focus on PnL, Volume, and Frequency.
