# market-analytics
An analytics project detailing trends on assets and macroeconomic indicators to answer the questions

## Problem

The markets are trending upward, but not everyone is investing. Also, the value of money is declining as the value of assets is increasing, so it's twice as important that ordinary people invest in the markets. 

However, people are concerned because they may lack an understanding of what they're investing in, and how to go about it. 

## Data

The data here provides insight into the way markets are moving, and shows scenarios indicating how much the user could gain from participating. 

Using data from Yahoo Finance, we provide data on assets (e.g. S&P500 ETF, AAPL, Gold and BTC) and macroeconomic indicators (e.g. inflation, output). 

## Architecture

We use the Python library yfinance to connect to Yahoo Finance's API. From here, we build Pandas DataFrames to construct the data tables. 

We serve the data tables to Streamlit to compute the visualisations and publish the data application.

## What this shows

We quantify the problem to the user. Then, we answer the question of 'So What?' with scenarios indicating the possible gains based on past returns. 

Then, we minimise the friction to action with a direct Call-To-Action with links to get started with investing, 

## What to do next

Next steps...

