# Stock Analyzer [![Build Status](https://travis-ci.org/ogoyal/StockAnalyzer.svg?branch=master)](https://travis-ci.org/ogoyal/StockAnalyzer)

### Run make
```
make
```

Runs python program to produce a stock data csv file. Program uses google finance api to pull stock info.

Today's data:

| Date| Stocks| Price($) | 
| --- | --- | ---  | 
| 2017-09-01| COST| 157.97 | 
| 2017-09-01| ATVI| 64.99 | 
| 2017-09-01| MSFT| 73.92 | 
| 2017-09-01| GE| 24.98 | 
| 2017-09-01| BA| 241.44 | 
| 2017-09-01| AMD| 13.37 | 
| 2017-09-01| BOX| 19.18 | 
| 2017-09-01| FB| 172.35 | 
| 2017-09-01| AMZN| 981.46 | 
| 2017-09-01| PCG| 69.89 | 
| 2017-09-01| AAPL| 164.07 | 
| 2017-09-01| AMC| 14.00 | 
| 2017-09-01| P| 8.41 | 
| 2017-09-01| WMT| 78.38 | 
| 2017-09-01| FDX| 215.83 | 

### Build/Run project

Program will monitor stocks daily. Append your list of stocks in tickers.txt

### APIs
googlefinance 0.7 : Python module to get stock data from Google Finance

```
pip install googlefinance
```

