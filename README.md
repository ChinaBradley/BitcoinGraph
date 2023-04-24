# Bitcoin Price Tracking with Candlestick Graph

## Introduction 
I will be using CoinGeco API to get the Price data for Bitcoin for 30 days with 24 observations per day (1 per hour). I will then create candlestick graphs that show the max, min, open, and close price per day.

## Goal
The goal of this project was to create an interactive visualization to track the price of Bitcoin. 

## Technology
- Python
- pandas
- numpy
- plotly
- pycoingeko
- mplfinance


## Approach
For this Bitcoin price tracking project, I used the CoinGeco API to retrieve the data. Then, I extracted the price data and converted it into a dataframe. To make the data more usable, I converted the timestamp to datetime and created a Date column. The next step was to find the minimum, maximum, open, and close prices for each day. Finally, I displayed the data in a visually appealing candlestick graph using Plotly. 
   

## Conclusion
In conclusion, the candlestick graph shows that Bitcoin's price experienced a period of growth at the start of April 2023, followed by a decline. A noticeable trend was observed where a smaller difference between the open and closing amounts corresponded with a price decrease, and vice versa.

You can view an image of the candlestick graph below.

<img width="810" alt="image" src="https://user-images.githubusercontent.com/65142541/233917558-6d8c5f3f-d8ee-4310-9fa9-052f311e8f50.png">
