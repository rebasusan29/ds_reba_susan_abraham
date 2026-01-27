# Trader Behavior & Market Sentiment Analysis

**Candidate:** Reba Susan Abraham

**Role:** Junior Data Scientist Application

**Task:** Web3 Trading Team Assignment

---

## 📌 Project Overview
This repository contains a comprehensive analysis of the relationship between **Trader Performance** (PnL, Volume, Activity) and **Market Sentiment** (Fear & Greed Index). The goal was to identify behavioral inefficiencies and "hidden patterns" that could inform automated trading strategies.

## 📂 Repository Structure
[cite_start]This submission follows the strict folder structure required by the assignment instructions [cite: 32-52]:

```text
ds_reba_abraham/
├── notebook_1.ipynb         # Main analysis code (Google Colab compatible)
├── ds_report.pdf            # Executive summary and strategic insights
├── README.md                # Project documentation (this file)
├── csv_files/               # Data directory
│   ├── historical_data.csv  # Raw trader data
│   ├── fear_greed_index.csv # Raw sentiment data
│   └── processed_trade_data.csv # Cleaned & merged dataset
└── outputs/                 # Generated visualizations
    └── trader_behavior_analysis.png # Final analysis charts
```
# 🚀 How to Run

The analysis is self-contained in `notebook_1.ipynb`.

**Open in Google Colab:**  
[INSERT YOUR GOOGLE COLAB LINK HERE]

## Dependencies

- pandas  
- matplotlib  
- seaborn  

## Execution

Run all cells sequentially.  
The notebook will automatically:
- Load data from the `csv_files/` directory  
- Save the resulting charts to `outputs/`

---

## 📊 Key Insights ("Hidden Patterns")

The analysis uncovered distinct inefficiencies in retail trader behavior:

### The "Euphoria Trap"
Trader profitability peaks during **"Greed"** ($87.89/trade) but crashes by ~71% when sentiment shifts to **"Extreme Greed"** ($25.42/trade).  
This suggests traders fail to exit positions before market corrections.

### High Volume in Fear
The vast majority of trading activity (~72% of all trades) occurs during **"Fear"** periods.

### Neutral Stagnation
The lowest profitability ($22.23) occurs during **"Neutral"** sentiment, indicating that trend-following strategies struggle in choppy markets.

---

## ⚠️ Data Note

The assignment instructions referenced a **Leverage** column in the dataset. However, the provided `historical_data.csv` did not contain this field.

**Action Taken:**  
The analysis was adapted to focus strictly on:
- Closed PnL  
- Volume  
- Trade Frequency  

Risk analysis based on leverage was omitted due to missing data.
