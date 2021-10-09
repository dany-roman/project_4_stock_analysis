# Project 4: Stock Analysis for Top Five High-Tech Companies

# Objectives & Approach

## Project Objective
Create a neural network model that will predict stock prices of 5 top tech companies

## Dataset
Used a kaggle dataset with stock prices for:

- Advanced Micro Devices, Inc. (NASDAQ: AMD)
- Alphabet Inc Class A (NASDAQ: GOOGL)
- Helmerich & Payne, Inc. (NYSE: HP)
- Intel Corporation (NASDAQ: INTC)
- Tesla Inc. (NASDAQ: TSLA)


## Discussion Overview:
- Created a neural network regression model that attempts to predict the stock prices of 5 top tier tech companies 
- Requires further optimization to determine the best settings (# nodes, # layers, activation, etc)

## Data Preparation:
- Imported datasets of top tech companies into pandas as dataframes
- Dropped unnecessary columns (Dividends and Stock Splits)
- Imported Yahoo finance library into jupyter notebook and obtained the necessary information to match the training data columns. 
- Created a function to determine moving average of stock price based on 7, 14, and 21 days and ranges between opening and closing price and high and low prices.

## Approach

Raw Stock Data --(Pandad)--(Neural Network --> Prepped Stock Data --Tabeau--> Prediction Data


## Challenges
- Model recognizes the overall trends but overshoots its predictions
- Model struggles with high priced stock more than low priced stock (more variability)
- Time

## Source
- High-tech stock prices
- Stock Closing Price Prediction using Machine Learning Techniques

## Team members:

- Dany Roman
- Ishan Chakrabarty
- Jucary Estrada
- Morteza Akbari

## Tableau 
- Tableau was used to show visualization of our data results.
- Predicted Close vs. Actual Close was analyzed.
- Visualizations of the Tech Stocks are published.

https://public.tableau.com/app/profile/jucary.estrada/viz/TechStocks_16337459337510/Story1
