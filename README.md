# Prediction Markets → Stocks

A Python research project testing whether changes in prediction-market probabilities help forecast subsequent stock returns beyond stock, market and sector momentum.

This repository contains the public project showcase and derived evidence, with no raw equity feeds or credentials.

The initial development study includes 6,512 chronological forecasts across three M&A event families. Adding the prediction-market feature did not improve forecast error. A separate one-day bid/ask replay demonstrates execution safeguards and cost/latency sensitivity; it does not establish a profitable strategy.

The research framework uses Python, pandas, NumPy, DuckDB, Parquet and pytest. The research snapshot passed 793 automated tests. Economic mappings and an independent final test remain open.

Open `index.html` for the interactive project explanation or `evidence.json` for the derived metrics. Results are exploratory and must not be interpreted as validated investment performance.
