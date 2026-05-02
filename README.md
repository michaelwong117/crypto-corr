# Crypto Correlation Forecasting Final Project

## Python Dependencies

Use Python 3.10+.

```bash
python -m pip install numpy pandas matplotlib scikit-learn scipy torch jupyter nbformat nbconvert pyarrow ipympl yfinance
```

`yfinance` is only needed if the Yahoo data is rebuilt. If Yahoo download fails, ask me for the cached files below and place them in the project root.

## Run

```bash
jupyter lab final_notebook.ipynb
```

Then run all cells.

## Required Files to Run Without Queuing Yfinance (Will Sometimes Bottleneck)

Required `data/` files:

```text
data/yahoo_pit_liquidity_top50_2021_by_trailing_volume_daily.csv
data/yahoo_pit_liquidity_top50_2021_monthly_rebalance_selection.csv
data/yahoo_pit_liquidity_top50_2021_selected_log_returns.csv
data/yahoo_pit_liquidity_top50_2021_selected_log_returns_cleaned.csv
```

Required `outputs/` files:

```text
outputs/yahoo_crypto_universe_history_proxy.csv
outputs/yahoo_pit_liquidity_top50_2021_exclusion_audit.csv
outputs/yahoo_pit_liquidity_top50_2021_monthly_liquidity_universe_summary.csv
```
