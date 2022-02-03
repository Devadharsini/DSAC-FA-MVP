# DSAC-FA-MVP
***Financial consultations with AI-backed advice.***
For stock market, the update of information of tickers in high fidelity and high speed is critical for
investors. We here develop a platform based on powerful AI/ML algorithms that empower users to
have an extensive and exhaustive view in stock movements.

The project is divided to three major sectors: Dataset collection, the backend processing with Python-
based libraries, including analyzing data and visualization, and finalized with frontend coding and
clouding deployment.
Firstly, the information is collected with API. Yahoo finance API is a well-known source of information
about stock market. It provides stock tickers live data and their history, too. Pandas Datareader is a
Python tool that lets us construct a pandas DataFrame object from numerous online data sources. It&#39;s
often utilised for analysing real-time stock price data. Yahoo finance API is included in Datareader,
helping us collect the stock data at ease with several code lines.
The next analyzing is done with Pandas. Pandas is a Python package that allows you to work with
large data sets. It offers tools for data analysis, cleansing, exploration, and manipulation. Pandas
makes it possible to evaluate large amounts of data and provide conclusions based on statistical
theory. Pandas can clean up and produce readable and useful data collections. The collected data
are stored in a cloud hosted NoSQL database for later access.
The clients or investors can have clear imaginations of stock trends through visualization. Our
platform can generate various interactive figures of a chosen ticker, including history fluctuation,
average values over time or even the future direction.

#install this prior to running the codes.
pip install yfinance
pip install pandas_datareader

#libraries to be imported
import pandas as pd
import datetime
import pandas_datareader.data as web
from pandas import Series, DataFrame
from pandas.plotting import scatter_matrix
import math
import numpy as np
from sklearn import preprocessing
import csv 
import json


