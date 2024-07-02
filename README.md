---
title: '3,468 days of Bitcoin history'
author: 'César Heredia, data journalist'
description: 'A detailed look at the behavior of the quintessential cryptocurrency since 2015'
modified: '2024-06-29'
files: ['btc_coingecko.csv','btc_year.csv','btc_month.csv','variation.csv','month_var.csv','year_var.csv']
group: 'Cryptocurrencies'
---

What a rollercoaster for Bitcoin! From its [initial monetary value](https://www.forbes.com/advisor/in/investing/cryptocurrency/bitcoin-price-history-chart/#:~:text=What%20Price%20Did%20Bitcoin%20Start,a%20value%20of%20%240.0009%20each.) [to the guy who paid two pizzas with 10,000 bitcoins on May 22, 2010](https://news.bitcoin.com/14-years-ago-an-individual-offered-10000-bitcoins-for-2-pizzas-finalizing-the-deal-in-4-days/), to the current price, much water has passed under the bridge.

From an initial estimated value of 0.0009, Bitcoin wasn't even worth a buck until February, 2011. Months later, its cotization began to scale. It reached 30 dollars for the first time in July but dropped to 2 dollars just six months later.

In 2012, Bitcoin broke the 100-dollar barrier for the first time on April 11, and in 2013, the 1,000-dollar barrier, however rapidly fell to 559.36 dollars on December 17.

2014 was not a good year, despite reaching a maximum of 936.4 dollars on January 5. It ended that year at 314 dollars, a value loss of two-thirds.

## What happened next?

Coingecko, the world's largest independent aggregator of cryptocurrency data, has historical Bitcoin price data public since January 1, 2015. The following table shows the daily price from that date through June 30, 2024. That's nine and a half years or, looked at another way, 114 months, or 3,468 days of Bitcoin prices at our disposal to perform the most interesting analyses.

#### Bitcoin daily price from January 1, 2015 to June 30, 2024 (USD)
<FlatUiTable
  data={{
    url: 'btc_coingecko.csv'
  }}
/>

In that span, Bitcoin went from the lowest price (172 dollars on January 14, 2015) to 73,098 dollars (on March 14, 2024), the highest value reached until now. How many dollars would represent that day the two pizzas bought in 2010 for 10,000 bitcoins? A hint: it's **a number of nine figures**!

#### Bitcoin daily price from January 1, 2015 to June 30, 2024
<PlotlyBarChart
  data={{
    url: 'btc_coingecko.csv'
  }}
  title="BTC average price per day (USD)"
  xAxis="date"
  yAxis="price"
/>

### Milestones

Bitcoin reached the following milestones on these dates:

 - 10k: November 28, 2017.
 - 20k: December 17, 2020.
 - 30k: January 3, 2021.
 - 40k: January 9, 2021.
 - 50k: February 18, 2021.
 - 60k: March 14, 2021.
 - 70k: March 12, 2024.

So, there is no surprise when you look at the **YoY average price variation** from 2020 to 2021: an increase of 329.3%. However, the maximum percent variation occurred between 2016 and 2017 (609%). The only significant decrease was from 2021 to 2022 (-40.4%).

#### Bitcoin YoY price variation from 2015 to June 2024 (%)
<FlatUiTable
  data={{
    url: 'year_var.csv'
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

In 54.4% of the 3,468 days analyzed in this report, there was an increase in Bitcoin's price. The days in which the price rose the most were:

 - December 7, 2017: 33.3%.
 - January 15, 2015: 22.3%.
 - July 20, 2017: 21.6%.
 - February 9, 2021: 19.2%.
 - April 3, 2019: 17.3%.
 - October 26, 2019: 16.4%.
 - December 26, 2017: 16.2%.
 - September 15, 2017: 15.7%.
 - January 5, 2017, and March 20, 2020: 14.8%.

The steepest declines occurred on the following dates:

 - March 13, 2020: -5.2%.
 - January 14, 2015: -22.3%.
 - September 14, 2017: -20.2%.
 - January 16, 2018: -18.7%.
 - February 6, 2018: -17.6%.
 - January 13, 2015: -17.5%.
 - June 14, 2022: -15.8%.
 - November 10, 2022: -15.2%.
 - January 15, 2016: -14.8%
 - August 2, 2016: -14.6%.

#### Bitcoin daily price variation from January 1, 2015 to June 30, 2024 (%)
<FlatUiTable
  data={{
    url: 'variation.csv'
  }}
/>

## Month-Over-Month

Some of the biggest monthly percent price variations of Bitcoin happened in 2017 between June and December. From November to December, **Bitcoin almost doubled its value** (an astonishing 99%).

#### Bitcoin monthly average price from January 2015 to June 2024
<PlotlyBarChart
  data={{
    url: 'btc_month.csv'
  }}
  title="BTC average price per month (USD)"
  xAxis="month"
  yAxis="avg"
/>

#### Bitcoin monthly price variation from January 2015 to June 2024 (%)
<FlatUiTable
  data={{
    url: 'month_var.csv'
  }}
/>


Note for the graphics: all prices at 00:00:00 GMT
Source: [Coingecko](https://www.coingecko.com/es/monedas/bitcoin/historical_data)
