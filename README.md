# Trader Behavior Analysis – Fear vs Greed

## Objective
Analyze how Bitcoin market sentiment (Fear vs Greed) affects trader behavior and performance using Hyperliquid trading data and the Bitcoin Fear & Greed Index.

## Key Questions
- Do traders perform better during Fear or Greed regimes?
- Are traders more risk-seeking during Greed?
- Are some traders consistently profitable regardless of sentiment?
- What patterns can inform smarter trading strategies?

## Project Structure
ds_<candidate_name>/
├── notebook_1.ipynb
├── notebook_2.ipynb
├── csv_files/
│   ├── historical_data.csv
│   └── fear_greed_index.csv
├── outputs/
│   └── *.png
├── ds_report.pdf
└── README.md

## Analysis Approach
- Cleaned and standardized trading data
- Engineered profitability and risk metrics
- Identified consistent trader performance
- Detected data limitation due to temporal mismatch
- Applied sentiment-based interpretation conceptually

## Key Insights
- Risk-adjusted consistency outperforms aggressive trading
- High trade frequency does not imply profitability
- Controlled downside risk is crucial for long-term success
- Sentiment-aware strategies can enhance risk management

## How to Run
1. Open `notebook_1.ipynb`
2. Run all cells top to bottom
3. Generated plots are saved in `outputs/`

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
