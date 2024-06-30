---
title: 'Bitcoin price from January 1, 2015 to June 30, 2024'
author: 'César Heredia, data journalist'
description: 'An analysis about the Bitcoin daily price data from Coingecko'
modified: '2024-06-29'
files: ['btc_main.csv','btc_year_avg.csv','btc_monthly_avg.csv']
group: 'Cryptocurrencies'
---

#### Bitcoin daily price from January 1, 2015 to June 30, 2024 (USD)

<FlatUiTable
  data={{
    url: 'btc_main.csv'
  }}
/>

#### Bitcoin monthly average price from January, 2015 to June, 2024
<PlotlyBarChart
  data={{
    url: 'btc_monthly_avg.csv'
  }}
  title="BTC average price per month (USD)"
  xAxis="month"
  yAxis="avg"
/>

#### Bitcoin yearly average price from 2015 to June, 2024
<PlotlyBarChart
  data={{
    url: 'btc_year_avg.csv'
  }}
  title="BTC average price per year (USD)"
  xAxis="year"
  yAxis="avg"
/>

Note for the graphics: all prices at 00:00:00 GMT
Source: [Coingecko](https://www.coingecko.com/es/monedas/bitcoin/historical_data)
