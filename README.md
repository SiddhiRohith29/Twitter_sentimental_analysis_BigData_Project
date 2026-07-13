# Twitter Sentiment Analysis → Predicting Stock Market Trends 📈

**DATA603 (Big Data Processing) team project · UMBC** — does public sentiment on Twitter move with a company's stock? We measured it for five of the biggest tickers on the market.

## Problem

Retail investors and analysts constantly speculate that "Twitter mood" leads price action. We tested the idea at scale: collect tweets about **Apple, Amazon, Google, Microsoft, and Tesla**, score their sentiment, and compare sentiment trends against stock-market movement.

## Approach

1. **Collection & processing at scale** — tweet datasets per ticker processed with big-data tooling (PySpark/Python) — cleaning, deduplication, tokenization.
2. **Sentiment scoring** — classify each tweet positive / negative / neutral and aggregate into time-series sentiment signals per company.
3. **Market comparison** — align sentiment series with stock trends and visualize the relationship.
4. **Visualization** — one **Tableau workbook per ticker** (see `Tableau outputs/`: `apple.twb`, `amazon.twb`, `Google.twb`, `Microsoft.twb`, `tesla.twb`), plus in-notebook charts.

## Repo structure

```
├─ Code/               # PySpark/Python notebook: pipeline + analysis + embedded Tableau views
└─ Tableau outputs/    # 5 Tableau workbooks — one per ticker
```

## Team

Akhilteja Jampani · Chaturya Gajula · Santosh Kumar Velgapuri · **Siddhidhatri Rohith Reddy Jaggari**

## Author links

[LinkedIn](https://www.linkedin.com/in/siddhidhatri-rohith-reddy-jaggari) · [GitHub](https://github.com/SiddhiRohith29)
