# CCXT-Price-Fetcher
This python project uses the CCXT library and public APIs from different crypto exchanges to fetch prices and comapre them with other crypto exchanges and give the price difference of each common coin and profit if 100$ was traded between them

# Crypto Price Difference Finder

This is a small project that uses the CCXT library and fetches cryptocurrency prices from various exchanges and identifies the price differences 
between them, potentially highlighting arbitrage opportunities.

## Features
- Fetches data from multiple exchanges
- Calculates price differences for each coin
- Sorts and lists coins with the highest price differences
- Estimates potential profit from arbitrage opportunities

## Installation

1. Clone the repository
   ```sh
   git clone https://github.com/fuzzylogic102/CCX-addon.git
   ```
2. Install the required dependencies
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Run the script
   ```sh
   python ccx_addon.py
   ```

## Example Output
```
Top 5 coins with highest price difference:
BTC has a price difference of 200.00 USD between binance and kraken.
Trading $100 between binance and kraken for BTC would yield a profit of 5.00 USD.
```
