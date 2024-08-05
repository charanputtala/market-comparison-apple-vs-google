# Stock Market Comparison Analysis

Stock Market Comparison Analysis is a methodical examination of multiple stocks or financial assets within the stock market. It involves analyzing the performance of various stocks or assets to gain insights into how they have fared relative to each other and the broader market. This analysis helps investors, financial analysts, and decision-makers make informed investment decisions.

## Process Overview

Below is the process we can follow for the task of Stock Market Performance Analysis as a Data Science professional:

1. Gather historical stock price data for the companies or financial instruments you want to compare.
2. Clean and preprocess the collected data.
3. Create relevant features or variables that can help in the comparison.
4. Ensure that the data for different stocks is aligned in terms of time.
5. Use data visualization techniques to present the comparison effectively.
6. Apply statistical methods to identify patterns or relationships between the stocks being compared.
7. Compare the performance of the selected stocks or financial instruments against relevant benchmarks, such as market indices like the S&P 500.

## Stock Market Comparison Analysis using Python

This project involves comparing the stock prices of Apple and Google using Python. Below is a detailed walkthrough of the process and code implementation.

### Data Collection

To start, we collected stock price data of Apple and Google for the last quarter using the Yahoo Finance API. The data was collected by installing the `yfinance` package.

```sh
pip install yfinance
