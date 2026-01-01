# Bitcoin Market Sentiment vs Trader Performance

## Objective
The goal of this project is to analyze how Bitcoin market sentiment
(Fear and Greed) affects trader behavior and trading performance.

## Datasets Used
1. Bitcoin Market Sentiment Dataset  
   - Contains daily market sentiment (Fear or Greed)

2. Historical Trader Data (Hyperliquid)  
   - Contains trade-level data such as PnL, size, side, and time
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


## Approach
- Cleaned and preprocessed both datasets
- Merged trader data with daily sentiment
- Analyzed performance metrics under Fear and Greed
- Identified behavioral and risk patterns

## Key Insights
- Traders perform more consistently during Fear
- Greed leads to larger trade sizes and higher losses
- Risk-adjusted returns are better in Fear periods
- Sentiment-aware traders outperform others

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib

## How to Run the Project
1. Install required libraries using `requirements.txt`
2. Open the Jupyter notebook
3. Run all cells from top to bottom
