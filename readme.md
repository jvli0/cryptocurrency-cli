# Cryptocurrency CLI

Cryptocurrency CLI lets you monitor cryptocurrencies in your portfolio and track your earnings through the command line.  It uses the coinmarketcap.com API to fetch crypto data.

![Cryptocurrency CLI](https://i.imgur.com/t51gp74.png)

## Features

### General
1. Command Line Interface
1. Supports the top 100 coins based on market cap
1. Track your portfolio holdings

### Bar Graph
1. Percentage breakdown of holdings
2. Colored Horizontal Bars
3. Portfolio value

### Crypto Table
1. Coin Rank
1. Price
1. Coins Owned
1. Net Worth
1. 24 Hour Volume
1. Market Cap
1. % Change 1 Hour
1. % Change 1 Day
1. % Change 1 Week
1. Last Updated

## Installation Instructions


1. Git Clone the repo

    ```
    git clone https://github.com/jvli0/cryptocurrency-cli/
    ```

1. Enter the repository

    ```
    cd cryptocurrency-cli && npm install
    ```

1. Run

    ```
    npm start
    ```

1. Edit portfolio.json

    ```json
    {
      "bitcoin": ".002",
      "litecoin": "1",
      "ethereum": ".095",
      "dogecoin": "10000"
    }
    ```
