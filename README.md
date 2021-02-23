# Stock Market Prediction using Machine Learning

This repository contains code and associated files for the stock market prediction using Machine Learning.

## Project Overview

Between 2010 and 2020 the S&P 500 has an annual average return of 13.6% in the past 10 years. This project would provide a practical approach to predict future price movements in financial markets based on past returns. The assumption is that certain patterns in financial markets repeat themselves such that past observations can be leveraged to predict future price movements. (Hilpisch, Yves. 2020. Artificial Intelligence in Finance: A Python-Based Guide.)

The data set is a 10-year trading data of SPY from January 2021 to the most recent date February 2021. SPY is a stock market index that measures the stock performance of 500 large companies listed on stock exchanges in the US. This fund is the largest ETF in the world. The SPY movement could signal the direction of the market.

**Requirements**
* Python 3.7
* Anaconda
* Keras
* TensorFlow
* pip

**Installation**
* Get into the project folder
* Setting up and activate the virtual env

**Install pandas_datareader library**
* conda install -c anaconda pandas-datareader

**Install ta-lib library**
* brew install ta-lib
* pip install ta-lib

**Install statsmodels library**
* conda install -c anaconda statsmodels

- - - -

> If you want to run prediction on any other stock, you can change the stock symbol in the DataReader and run the models.