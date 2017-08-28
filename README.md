# Stock Analyzer [![Build Status](https://travis-ci.org/ogoyal/StockAnalyzer.svg?branch=master)](https://travis-ci.org/ogoyal/StockAnalyzer)

### Run make
```
make
```

Runs python program to produce a stock data csv file. Program uses google finance api to pull stock info.

Today's data:

| Date| Stocks| Price($) | 
| --- | --- | ---  | 
| 2017-08-28| COST| 152.95 | 
| 2017-08-28| ATVI| 62.96 | 
| 2017-08-28| MSFT| 72.83 | 
| 2017-08-28| GE| 24.50 | 
| 2017-08-28| BA| 235.91 | 
| 2017-08-28| AMD| 12.22 | 
| 2017-08-28| BOX| 19.80 | 
| 2017-08-28| FB| 167.57 | 
| 2017-08-28| AMZN| 951.53 | 
| 2017-08-28| PCG| 70.14 | 
| 2017-08-28| AAPL| 161.80 | 
| 2017-08-28| AMC| 12.98 | 
| 2017-08-28| P| 8.10 | 
| 2017-08-28| WMT| 78.17 | 
| 2017-08-28| FDX| 208.10 | 

### Build/Run project

Program will monitor stocks daily. Append your list of stocks in tickers.txt

### APIs
googlefinance 0.7 : Python module to get stock data from Google Finance

```
pip install googlefinance
```

