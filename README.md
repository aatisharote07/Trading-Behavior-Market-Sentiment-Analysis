# Data Science Assignment - Trading Behavior & Market Sentiment


## Project Overview
Analysis of the relationship between Hyperliquid trader behavior and Bitcoin market sentiment (Fear & Greed Index).

## Repository Structure
```
ds_antigravity/
├── notebook_1.ipynb          
├── csv_files/                
│   ├── merged_daily_metrics.csv
│   ├── trader_level_metrics.csv
│   ├── profitability_by_sentiment.csv
│   ├── fear_vs_greed_comparison.csv
│   ├── predictive_signals.csv
│   ├── trader_styles.csv
│   
├── outputs/                  
│   ├── summary_dashboard.png
│   ├── pnl_by_sentiment.png
│   ├── correlation_matrix.png
│  
├── ds_report.md             
└── README.md                
```

## Key Findings

1. **Profitability**: Analyzed average daily PnL during Fear vs Greed periods.
2. **Risk Behavior**: Examined leverage usage and its correlation with market sentiment.
3. **Trader Styles**: Classified traders into Contrarian vs Momentum based on their performance across sentiments.

## How to Run

1. Open `notebook_1.ipynb` in Jupyter or Google Colab.
2. Ensure `historical_data.csv` and `fear_greed_index.csv` are in the expected directory .
3. Run all cells.

## Technologies Used
- Python 3.x
- Pandas, NumPy for data manipulation
- Matplotlib, Seaborn for visualization
- SciPy for statistical analysis
