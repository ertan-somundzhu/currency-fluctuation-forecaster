# currency-fluctuation-forecaster

This pet project is an extencsion of my abother pet project [cbr-scraper](https://github.com/ertan-somundzhu/cbr-scraper)

It uses the exchange rate info scraped by the cbr-scraper to construct a time series of currency rate movement to then forecast future movement

Currently the model is trained to forecast exchange rate of Brazilian Reais to one Russian Ruble

This code trains and returns *.sav file that contains an ML model trained to forecast Brazilian Reais

Libraries used: sklearn, skforecast, pandas, matplotlib, joblib


