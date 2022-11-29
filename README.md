# SIADS-Capstone-Volatility-Prediction


## Project Statement

Our project's objective is to predict the volatility of CBOE index. We will use multiple models including machine learning and volatility models to do the predictions. We also aim to compare forecasting using only past volatility values versus using other exogenous features.  

## Methodology

First, we did exploratory data analysis to our dataset which guided the pre-processing phase. Afterwards, we did the feature extraction phase from the existing features. Then we applied the different models across our two scenarios (having exogenous variables and not having them). Finally, we train the model with best performance and get the most important features.

## Data

We are using historical data from 1990 until now. We included additional exogenous data about:
- TNX: Treasury Yield 10 Years
- GSPC: S&P 500 
- GSCI: S&P GSCI Commodity Index
- GDP: Gross Domestic Product
- CPI: IQ Real Return ETF
- Dollar Index
- EPU: Economic Policy Uncertainty Index
- HSI: HANG SENG INDEX
- VKOSPI: Korea Stock Exchange KOSPI Index

## Sources

Data is downloaded from yahoo finance and the Fred. 

Papers:
- Machine Learning for Multi-step Ahead Forecasting of Volatility Proxies: https://ceur-ws.org/Vol-1941/MIDAS2017_paper3.pdf
- A machine learning approach to volatility forecasting : https://pure.au.dk/portal/files/208284743/rp21_03.pdf
- https://www.oreilly.com/library/view/machine-learning-for/9781492085249/ch04.html#idm45737244123312
