# JPM Forage Natural Gas Contract Prices
Trying out JP Morgan's Quant Project from the Forage Website. The projects asks us to predict Natural Gas Contract Prices. 

# Task 1: Natural Gas Price Estimation

Given a CSV file of monthly snapshots of contract prices, your goal is to produce a visual representation of the existing price data, as well as to extrapolate the prices for an extra year. This will help provide indicative prices for longer-term storage contracts.

## Steps to Complete the Task:

### 1. Download Monthly Natural Gas Price Data
   - Ensure you have access to reliable sources for downloading historical natural gas prices.
   - Download the data in a CSV format, ensuring that each point corresponds to the purchase price at the end of each month.

### 2. Data Range
   - The dataset should cover the price data from 31st October 2020 to 30th September 2024.
   - Ensure that the data is cleaned and pre-processed for analysis.

### 3. Price Estimation and Extrapolation
   - Analyze the historical price data to understand the trends and patterns.
   - Use statistical or machine learning models to estimate the purchase price of gas for any past date.
   - Extrapolate the data to predict prices for one year into the future.

### 4. Implement the Price Estimation Function
   - Write a function in your preferred programming language.
   - The function should take a date as input.
   - Return the estimated purchase price for the input date based on your analysis and extrapolation.

## Example Code (Python):
```python
import pandas as pd
# Assume you have loaded your data into a DataFrame named df

def estimate_price(date):
    # Your implementation here
    # Use the historical data to estimate the price for the given date
    pass

# Example usage:
price_estimate = estimate_price('2025-05-15')
print('Estimated Price:', price_estimate)
