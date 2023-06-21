﻿# crypto-prices-converter

**crypto-prices-converter** is an npm package that provides a simple way to retrieve cryptocurrency prices and convert them into different fiat currencies. It supports various cryptocurrencies, including Bitcoin, Ethereum, Binance Coin (BNB), Ripple (XRP), and more. The package requires the currency names to be specified in the format of lowercase ISO 4217 currency codes (e.g., "usd" for United States Dollar).

# Installation

To install **crypto-prices-converter**, use npm:

```bash
npm install crypto-prices-converter
```

# Usage

To use the package, you need to require the **crypto-prices-converter** module:

```js
const getCryptoPrice = require("crypto-prices-converter");
```

The **getCryptoPrice** function allows you to retrieve the price of a cryptocurrency in a specific fiat currency. It takes three parameters: the cryptocurrency symbol, the number of cryptocurrency and the fiat currency code. Here's an example:

```js
console.log(getCryptoPrice("bitcoin", 2, "usd"));
```

This will retrieve the current price of Bitcoin in US Dollars (USD) and log it to the console.

# Repository

For more information and updates, you can visit the GitHub repository of **crypto-prices-converter**:

**https://github.com/Mouizeddine/crypto-converter-library**

Feel free to explore the repository, contribute, or submit any issues or feature requests.
