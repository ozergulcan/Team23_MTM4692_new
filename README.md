# Multi-Exchange Crypto Arbitrage Detector

## 📊 Project Description
This project aims to detect arbitrage opportunities in cryptocurrency markets using SQL. Arbitrage refers to making profit from price differences of the same asset across different exchanges.

In this project, Bitcoin (BTC) price data from multiple exchanges is analyzed. The system compares prices across exchanges and identifies potential arbitrage opportunities by considering transaction costs.

## 📁 Datasets
The project uses historical BTC price data from the following exchanges:

- Binance (BTC/USDT)
- Coinbase (BTC/USD)
- Bitfinex (BTC/USD)
- Bitstamp (BTC/USD)

All datasets are stored in the `data/` folder.

## 🧠 Methodology
- Data from different exchanges is collected and standardized
- Price differences are calculated for the same timestamps
- Transaction costs (taker fees) are included in the calculations
- Only profitable arbitrage opportunities are selected

## 🏗️ System Design
The system is based on a relational database structure with the following main tables:

- Exchanges
- Assets
- MarketData
- TradingFees

Data from different exchanges is combined into a single structure to allow comparison across markets.

## ⚙️ Technologies Used
- SQL (data storage and analysis)
- CSV datasets
- GitHub (version control)

  ## 🌐 Web Application
A web application will be developed to visualize arbitrage opportunities.

Technologies used:
- Python
- Streamlit (for building the web interface)
- Pandas (data processing)

The application will allow users to:
- Compare prices across exchanges
- View arbitrage opportunities
- Analyze price differences over time

