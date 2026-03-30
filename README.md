# 📈 Market Sentiment & Trader Performance Analysis

An EDA project exploring how the Fear & Greed Index affects trader behavior and profitability on the Hyperliquid decentralized exchange.

## Objective
Uncover whether market sentiment (Fear vs Greed) impacts PnL, trade frequency, position sizing, and long/short ratios — and derive actionable trading strategies from the data.

## Datasets
| File | Description |
|---|---|
| `fear_greed_index.csv` | Daily Fear & Greed Index values with sentiment labels |
| `historical_data.csv` | Individual trade records (account, coin, size, side, PnL, fees, timestamp) |

## Tech Stack
`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Google Colab`

## Key Findings
- **Fear days produce the highest avg PnL** — experienced traders are contrarian, buying dips and profiting on recovery
- **Traders are most active on Fear days** (~1,300 trades/day) with the largest position sizes (~$7,700 avg)
- **Only 9.4% of traders are loss makers** — healthier than typical retail markets
- **High-frequency traders earn ~2.7× more** than medium-frequency traders
- Extreme Greed (Oct–Nov 2024, F/G index 85–95) produced the highest aggregate PnL ever (~$225K)

## Trading Strategies Derived
| Sentiment | Recommended Action |
|---|---|
| Fear | Reduce size 30–40%, wait for clearer setups |
| Neutral | Standard size, enter on clear signals only |
| Greed | Full size, momentum strategies work best |

## How to Run
```bash
git clone <your-repo-url>
# Upload fear_greed_index.csv and historical_data.csv to /content/ in Colab
# Run all cells top to bottom
```

## Project Structure
```
├── Market_Sentiment_Trader_Performance_Analysis.ipynb
├── fear_greed_index.csv
├── historical_data.csv
└── README.md
```
