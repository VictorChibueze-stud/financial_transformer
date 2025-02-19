<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" class="logo" width="120"/>

# Multi-Timeframe Transformer for Robust Trading Bots

---

## Project Overview

This project explores the use of transformer models to build robust trading bots based solely on OHLC (Open, High, Low, Close) data and features derived from them. A key innovation of this project is the encoding of relationships between multiple timeframes, allowing the model to capture market dynamics at various scales.

## Features

- Utilizes transformer architecture for time series prediction
- Incorporates multi-timeframe data (e.g., 1min, 5min, 15min, 1h, 4h)
- Derives features from OHLC data across timeframes
- Encodes timeframe relationships for optimal transformer input
- Aims to create robust trading strategies


## Usage

(To be updated as the project progresses)

## Project Structure

```
.
├── data/
│   ├── raw/
│   └── processed/
├── models/
├── src/
│   ├── data_processing/
│   ├── feature_engineering/
│   ├── model/
│   └── evaluation/
├── notebooks/
├── tests/
├── config.yaml
├── requirements.txt
└── README.md
```


## Key Components

1. **Data Processing**: Scripts for fetching and preprocessing OHLC data from multiple timeframes.
2. **Feature Engineering**: Tools for deriving technical indicators and other features from OHLC data.
3. **Timeframe Encoding**: (To be developed) Novel method for encoding relationships between different timeframes.
4. **Transformer Model**: Implementation of a transformer architecture adapted for multi-timeframe financial data.
5. **Trading Bot**: Logic for executing trades based on model predictions.
6. **Evaluation**: Backtesting and performance metrics for the trading bot.


