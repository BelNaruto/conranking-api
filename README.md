# CoinRanking API

The **CoinRanking API** is your go-to resource for real-time cryptocurrency data, offering developers and crypto enthusiasts a robust platform to access information on various cryptocurrencies, market trends, and price statistics. With comprehensive endpoints, you can easily integrate cryptocurrency data into your applications. This API can be found on RapidApi. [Click here to access it](https://rapidapi.com/belchiorarkad-FqvHs2EDOtP/api/coinranking-api1).

## Getting Started

1. **Sign Up**: Create an account on RapidAPI.
2. **Subscribe**: Choose a pricing plan that suits your needs.
3. **API Key**: Obtain your unique API key to start making requests.
4. **Documentation**: For detailed instructions, check out the [CoinRanking API Documentation](https://rapidapi.com/belchiorarkad-FqvHs2EDOtP/api/coinranking-api1).


## Key Features

- **Real-Time Prices**: Access up-to-date prices for a wide range of cryptocurrencies.
- **Market Data**: Retrieve detailed market information, including market cap, volume, and historical data.
- **Cryptocurrency Listings**: Get information on top cryptocurrencies by market capitalization and other metrics.
- **Exchange Rates**: Obtain current exchange rates between different cryptocurrencies and fiat currencies.


## Get Currencies Reference

This API endpoint retrieves Currencies Reference with the specified parameters.

### Parameters

- `page` (Default: '0'): The page number for paginated results.
- `limit` (Default: '30'): The maximum number of results to return per page.


## Get Search

This API endpoint retrieves results from search with the specified parameters.

### Parameters

- `query` (* required): The query to search.
- `page` (Default: '0'): The page number for paginated results.
- `limit` (Default: '50'): The maximum number of results to return per page.
- `currencyUuid` (Default: 'yhjMzLPhuIDl'): The currency UUID for the desired currency. Use 'yhjMzLPhuIDl' for USD or '5k-_VTxqtCEI' for Euro. More currencies can be obtained from the endpoint `/currency-converter`.
- `timePeriod` (Default: '24h'): The time period for which to retrieve data. Available options include: '1h', '3h', '12h', '24h', '7d', '30d', '3m', '1y', '3y', '5y'.

For more details and examples for currencyUuid, refer to the documentation or endpoint `/currency-converter`.


## Get Market Stats

This API endpoint retrieves Market Stats with the specified parameters.

### Parameters

- `currencyUuid` (Default: 'yhjMzLPhuIDl'): The currency UUID for the desired currency. Use 'yhjMzLPhuIDl' for USD or '5k-_VTxqtCEI' for Euro. More currencies can be obtained from the endpoint `/currency-converter`.
- `timePeriod` (Default: '24h'): The time period for which to retrieve data. Available options include: '1h', '3h', '12h', '24h', '7d', '30d', '3m', '1y', '3y', '5y'.

For more details and examples for currencyUuid, refer to the documentation or endpoint `/currency-converter`.


## Get Coin Losers
This API endpoint retrieves Coin Losers with the specified parameters.

### Parameters

- `page` (Default: '0'): The page number for paginated results.
- `limit` (Default: '50'): The maximum number of results to return per page.
- `currencyUuid` (Default: 'yhjMzLPhuIDl'): The currency UUID for the desired currency. Use 'yhjMzLPhuIDl' for USD or '5k-_VTxqtCEI' for Euro. More currencies can be obtained from the endpoint `/currency-converter`.
- `timePeriod` (Default: '24h'): The time period for which to retrieve data. Available options include: '1h', '3h', '12h', '24h', '7d', '30d', '3m', '1y', '3y', '5y'.

For more details and examples for currencyUuid, refer to the documentation or endpoint `/currency-converter`.

## Get Coin Top Gainers

This API endpoint retrieves Coin Top Gainers with the specified parameters.

### Parameters

- `page` (Default: '0'): The page number for paginated results.
- `limit` (Default: '50'): The maximum number of results to return per page.
- `currencyUuid` (Default: 'yhjMzLPhuIDl'): The currency UUID for the desired currency. Use 'yhjMzLPhuIDl' for USD or '5k-_VTxqtCEI' for Euro. More currencies can be obtained from the endpoint `/currency-converter`.
- `timePeriod` (Default: '24h'): The time period for which to retrieve data. Available options include: '1h', '3h', '12h', '24h', '7d', '30d', '3m', '1y', '3y', '5y'.

For more details and examples, refer to the documentation or endpoint `/currency-converter`.


## Get Coins By Category

This API endpoint retrieves Coins By Category with the specified parameters.

### Parameters

- `tag` (Default: 'meme'): The tags for the category. Available: base-meme | meme | solana-meme | rwa | ai | layer-1 | layer-2 | brc-20 | drc-20
- `page` (Default: '0'): The page number for paginated results.
- `limit` (Default: '50'): The maximum number of results to return per page.
- `currencyUuid` (Default: 'yhjMzLPhuIDl'): The currency UUID for the desired currency. Use 'yhjMzLPhuIDl' for USD or '5k-_VTxqtCEI' for Euro. More currencies can be obtained from the endpoint `/currency-converter`.
- `timePeriod` (Default: '24h'): The time period for which to retrieve data. Available options include: '1h', '3h', '12h', '24h', '7d', '30d', '3m', '1y', '3y', '5y'.

For more details and examples, refer to the documentation or endpoint `/currency-converter`.



## Get New Coins

This API endpoint retrieves New Coins with the specified parameters.

### Parameters

- `page` (Default: '0'): The page number for paginated results.
- `limit` (Default: '50'): The maximum number of results to return per page.
- `currencyUuid` (Default: 'yhjMzLPhuIDl'): The currency UUID for the desired currency. Use 'yhjMzLPhuIDl' for USD or '5k-_VTxqtCEI' for Euro. More currencies can be obtained from the endpoint `/currency-converter`.
- `timePeriod` (Default: '24h'): The time period for which to retrieve data. Available options include: '1h', '3h', '12h', '24h', '7d', '30d', '3m', '1y', '3y', '5y'.

For more details and examples for currencyUuid, refer to the documentation or endpoint `/currency-converter`.



## Get Coin Markets

This API endpoint retrieves coin markets with the specified parameters.

### Parameters

- `page` (Default: '0'): The page number for paginated results.
- `limit` (Default: '50'): The maximum number of results to return per page.
- `currencyUuid` (Default: 'yhjMzLPhuIDl'): The currency UUID for the desired currency. Use 'yhjMzLPhuIDl' for USD or '5k-_VTxqtCEI' for Euro. More currencies can be obtained from the endpoint `/currency-converter`.
- `timePeriod` (Default: '24h'): The time period for which to retrieve data. Available options include: '1h', '3h', '12h', '24h', '7d', '30d', '3m', '1y', '3y', '5y'.

For more details and examples for currencyUuid, refer to the documentation or endpoint `/currency-converter`.


## Get Coin Available Exchanges

This API endpoint retrieves coin exchanges with the specified parameters.

### Parameters

- `page` (Default: '0'): The page number for paginated results.
- `limit` (Default: '50'): The maximum number of results to return per page.
- `currencyUuid` (Default: 'yhjMzLPhuIDl'): The currency UUID for the desired currency. Use 'yhjMzLPhuIDl' for USD or '5k-_VTxqtCEI' for Euro. More currencies can be obtained from the endpoint `/currency-converter`.


For more details and examples, refer to the documentation or endpoint `/currency-converter`.


## Get Coin Histort

This API endpoint retrieves coin history with the specified parameters.

### Parameters

- `currencyUuid` (Default: 'yhjMzLPhuIDl'): The currency UUID for the desired currency. Use 'yhjMzLPhuIDl' for USD or '5k-_VTxqtCEI' for Euro. More currencies can be obtained from the endpoint `/currency-converter`.
- `timePeriod` (Default: '24h'): The time period for which to retrieve data. Available options include: '1h', '3h', '12h', '24h', '7d', '30d', '3m', '1y', '3y', '5y'.

For more details and examples for currencyUuid, refer to the documentation or endpoint `/currency-converter`.


## Get Coin Details

This API endpoint retrieves coin details with the specified parameters.

### Parameters
- `currencyUuid` (Default: 'yhjMzLPhuIDl'): The currency UUID for the desired currency. Use 'yhjMzLPhuIDl' for USD or '5k-_VTxqtCEI' for Euro. More currencies can be obtained from the endpoint `/currency-converter`.
- `timePeriod` (Default: '24h'): The time period for which to retrieve data. Available options include: '1h', '3h', '12h', '24h', '7d', '30d', '3m', '1y', '3y', '5y'.

For more details and examples for currencyUuid, refer to the documentation or endpoint `/currency-converter`.


## Get Coin Prices

This API endpoint retrieves coin prices with the specified parameters.

### Parameters

- `page` (Default: '0'): The page number for paginated results.
- `limit` (Default: '50'): The maximum number of results to return per page.
- `currencyUuid` (Default: 'yhjMzLPhuIDl'): The currency UUID for the desired currency. Use 'yhjMzLPhuIDl' for USD or '5k-_VTxqtCEI' for Euro. More currencies can be obtained from the endpoint `/currency-converter`.
- `timePeriod` (Default: '24h'): The time period for which to retrieve data. Available options include: '1h', '3h', '12h', '24h', '7d', '30d', '3m', '1y', '3y', '5y'.

For more details and examples for currencyUuid, refer to the documentation or endpoint `/currency-converter`.



## Get Exchange Markets

This API endpoint retrieves Exchange Markets with the specified parameters.

### Parameters

- `page` (Default: '0'): The page number for paginated results.
- `limit` (Default: '7'): The maximum number of results to return per page.
- `currencyUuid` (Default: 'yhjMzLPhuIDl'): The currency UUID for the desired currency. Use 'yhjMzLPhuIDl' for USD or '5k-_VTxqtCEI' for Euro. More currencies can be obtained from the endpoint `/currency-converter`.


For more details and examples for currencyUuid, refer to the documentation or endpoint `/currency-converter`.


## Get Exchange Available Coins

This API endpoint retrieves Exchange Available Coins with the specified parameters.

### Parameters

- `page` (Default: '0'): The page number for paginated results.
- `limit` (Default: '7'): The maximum number of results to return per page.
- `currencyUuid` (Default: 'yhjMzLPhuIDl'): The currency UUID for the desired currency. Use 'yhjMzLPhuIDl' for USD or '5k-_VTxqtCEI' for Euro. More currencies can be obtained from the endpoint `/currency-converter`.


For more details and examples for currencyUuid, refer to the documentation or endpoint `/currency-converter`.


## Get Coin Prices

This API endpoint retrieves coin prices with the specified parameters.

### Parameters

- `currencyUuid` (Default: 'yhjMzLPhuIDl'): The currency UUID for the desired currency. Use 'yhjMzLPhuIDl' for USD or '5k-_VTxqtCEI' for Euro. More currencies can be obtained from the endpoint `/currency-converter`.


For more details and examples for currencyUuid, refer to the documentation or endpoint `/currency-converter`.




## Get Exchange

This API endpoint retrieves exchange with the specified parameters.

### Parameters

- `page` (Default: '0'): The page number for paginated results.
- `limit` (Default: '50'): The maximum number of results to return per page.
- `currencyUuid` (Default: 'yhjMzLPhuIDl'): The currency UUID for the desired currency. Use 'yhjMzLPhuIDl' for USD or '5k-_VTxqtCEI' for Euro. More currencies can be obtained from the endpoint `/currency-converter`.
- `timePeriod` (Default: '24h'): The time period for which to retrieve data. Available options include: '1h', '3h', '12h', '24h', '7d', '30d', '3m', '1y', '3y', '5y'.

For more details and examples for currencyUuid, refer to the documentation or endpoint `/currency-converter`.



## Get Currency Converter

This API endpoint retrieves Currency Converter.


## Commonly Asked Questions

### 1. What kind of data can I access through the CoinRanking API?
You can access real-time prices, market data, cryptocurrency listings, and exchange rates.

### 2. How do I authenticate my API requests?
You need to include your API key in the headers of your requests as specified in the API documentation.

### 3. Are there any usage limits for the API?
Yes, usage limits depend on the subscription plan you select. Please check the RapidAPI dashboard for details.

### 4. Can I filter data by specific cryptocurrencies?
Yes, the API allows you to filter data based on specific cryptocurrencies by their IDs or symbols.

### 5. Is historical data available for cryptocurrencies?
Yes, the CoinRanking API provides endpoints for accessing historical price data and market trends.

For more information and to start using the CoinRanking API, visit [CoinRanking API on RapidAPI](https://rapidapi.com/belchiorarkad-FqvHs2EDOtP/api/coinranking-api1).




