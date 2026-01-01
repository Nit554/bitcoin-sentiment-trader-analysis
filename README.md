# bitcoin-sentiment-trader-analysis
Analyzing trader performance based on Bitcoin market sentiment (Fear vs Greed)
# Bitcoin Market Sentiment vs Trader Performance

## Objective
This project analyzes how Bitcoin market sentiment (Fear and Greed)
affects trader behavior and performance using historical trading data.

## Datasets
1. Bitcoin Market Sentiment Dataset (Fear / Greed)
2. Historical Trader Data from Hyperliquid
   ## Dataset Access

The datasets used in this project are larger than GitHub’s file size limit.

To run this project:

1. Download the datasets from the following source:
   - Bitcoin Fear & Greed Index (public dataset)
   - Hyperliquid historical trading data

2. Place the downloaded CSV files inside the `data/` folder:
   - fear_greed_index.csv
   - historical_data.csv

The notebook will run correctly once the files are added locally.


## Analysis Performed
- Data cleaning and preprocessing
- Sentiment-based performance analysis
- Risk-adjusted PnL using trade size
- Long vs Short behavior analysis
- Account-level performance evaluation

## Key Insights
- Traders perform more consistently during Fear
- Greed leads to overtrading and higher losses
- Sentiment-aware traders outperform others

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib

## How to Run
1. Install requirements
2. Open the Jupyter notebook
3. Run all cells
