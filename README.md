# SIADS-Capstone-Volatility-Prediction


## Project Statement

Our project's objective is to predict the volatility of CBOE index. We will use multiple models including machine learning and volatility models to do the predictions. We also aim to compare forecasting using only past volatility values versus using other exogenous features.  

## Methodology

First, we did exploratory data analysis to our dataset which guided the pre-processing phase. Afterwards, we did the feature extraction phase from the existing features. Then we applied the different models across our two scenarios (having exogenous variables and not having them). Finally, we compare the different models performance and decide on the best performing model.

## Data

We are using historical data from 1990 until 2022. 
- TNX: Treasury Yield 10 Years
- GSPC: S&P 500 
- GSCI: S&P GSCI Commodity Index
- GDP: Gross Domestic Product
- CPI: IQ Real Return ETF
- Dollar Index
- EPU: Economic Policy Uncertainty Index
- HSI: HANG SENG INDEX
- VKOSPI: Korea Stock Exchange KOSPI Index
- VIX: S&P 500 Volatility Index

## Sources (Data Access)

Data is downloaded from Yahoo Finance and the Fred. 

https://finance.yahoo.com/

https://fred.stlouisfed.org/
