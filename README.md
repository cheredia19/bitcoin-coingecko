---
title: 'Bitcoin price from January 1, 2015 to June 30, 2024'
author: 'César Heredia, data journalist'
description: 'An analysis about the Bitcoin daily price data from Coingecko'
modified: '2024-06-29'
files: ['btc_coingecko.csv','btc_year.csv','btc_month.csv','variation.csv','month_var.csv','year_var.csv']
group: 'Cryptocurrencies'
---

What a rollercoaster has been the Bitcoin! From its [initial monetary value](https://www.forbes.com/advisor/in/investing/cryptocurrency/bitcoin-price-history-chart/#:~:text=What%20Price%20Did%20Bitcoin%20Start,a%20value%20of%20%240.0009%20each.) [to the guy who paid two pizzas with 10,000 bitcoins on May 22, 2010](https://news.bitcoin.com/14-years-ago-an-individual-offered-10000-bitcoins-for-2-pizzas-finalizing-the-deal-in-4-days/), to the current price, much water has passed under the bridge.



## What happened next?

According to Coingecko, the world's largest independent cryptocurrency data aggregator, the table below shows the bitcoin historical price data from January 1, 2015 to June 30, 2024.

#### Bitcoin daily price from January 1, 2015 to June 30, 2024 (USD)
<FlatUiTable
  data={{
    url: 'btc_coingecko.csv'
  }}
/>

#### Bitcoin daily price from January 1, 2015 to June 30, 2024
<PlotlyBarChart
  data={{
    url: 'btc_coingecko.csv'
  }}
  title="BTC average price per day (USD)"
  xAxis="date"
  yAxis="price"
/>

#### Bitcoin monthly average price from January 2015 to June 2024
<PlotlyBarChart
  data={{
    url: 'btc_month.csv'
  }}
  title="BTC average price per month (USD)"
  xAxis="month"
  yAxis="avg"
/>

#### Bitcoin monthly variation price from January 2015 to June 2024 (%)
<FlatUiTable
  data={{
    url: 'month_var.csv'
  }}
/>

#### Bitcoin YoY average price from 2015 to June 2024
<PlotlyBarChart
  data={{
    url: 'btc_year.csv'
  }}
  title="BTC average price per year (USD)"
  xAxis="year"
  yAxis="avg"
/>

#### Bitcoin YoY variation price from 2015 to June 2024 (%)
<FlatUiTable
  data={{
    url: 'year_var.csv'
  }}
/>

#### Bitcoin daily variation from January 1, 2015 to June 30, 2024 (%)
<FlatUiTable
  data={{
    url: 'variation.csv'
  }}
/>

Note for the graphics: all prices at 00:00:00 GMT
Source: [Coingecko](https://www.coingecko.com/es/monedas/bitcoin/historical_data)
