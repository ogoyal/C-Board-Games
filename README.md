# CSVTableContainer
C++ Program using Standard Library

### Run make
```
make
```

Runs python program to produce a stock data csv file. Program uses yahoo-finance api to pull stock info.
Creates a C++ program to do data analytics.

Sample CSV data file:

| Date| Stocks| Price($)| Change($) | 
| --- | --- | --- | ---  | 
| 2016-09-30| COST| 152.51| +5.02 | 
| 2016-09-30| ATVI| 44.39| +0.18 | 
| 2016-09-30| MSFT| 57.60| +0.20 | 
| 2016-09-30| GE| 29.65| +0.12 | 
| 2016-09-30| BA| 131.74| +0.71 | 
| 2016-09-30| AMD| 6.91| +0.24 | 
| 2016-09-30| UPS| 109.52| +1.31 | 
| 2016-09-30| FB| 128.49| +0.40 | 
| 2016-09-30| AMZN| 837.31| +8.26 | 
| 2016-09-30| PCG| 61.17| -0.59 | 
| 2016-09-30| AAPL| 113.3052| +1.1252 | 
| 2016-09-30| AMC| 31.09| +0.29 | 
| 2016-09-30| NFLX| 98.55| +1.88 | 
| 2016-09-30| WMT| 72.12| +1.39 | 
| 2016-09-30| FDX| 175.00| -0.12 | 

### Build/Run project

Program will monitor stocks daily. Append your list of stocks in tickers.txt

### APIs
yahoo-finance 1.1.4 : Python module to get stock data from Yahoo! Finance

```
pip install yahoo-finance
```

