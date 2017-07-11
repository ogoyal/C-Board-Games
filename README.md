# Stock Analyzer

### Run make
```
make
```

Runs python program to produce a stock data csv file. Program uses yahoo-finance api to pull stock info.

Sample data:

| Date| Stocks| Price($)| Change($)| Change(%) | 
| --- | --- | --- | --- | ---  | 
| 2017-07-11| COST| 151.86| +0.86| +0.57% | 
| 2017-07-10| ATVI| 58.51| |  | 
| 2017-07-10| MSFT| 69.98| +0.52| +0.75% | 
| 2017-07-10| GE| 26.04| -0.11| -0.42% | 
| 2017-07-10| BA| 203.96| +1.59| +0.79% | 
| 2017-07-10| AMD| 13.81| +0.45| +3.37% | 
| 2017-07-10| BOX| 18.05| -0.14| -0.77% | 
| 2017-07-10| FB| 153.50| +2.06| +1.36% | 
| 2017-07-10| AMZN| 996.47| +17.71| +1.81% | 
| 2017-07-11| PCG| 64.955| -0.105| -0.161% | 
| 2017-07-10| AAPL| 145.06| +0.88| +0.61% | 
| 2017-07-10| AMC| 21.50| -0.45| -2.05% | 
| 2017-07-11| P| 9.085| +0.335| +3.829% | 
| 2017-07-10| WMT| 73.23| -2.10| -2.79% | 
| 2017-07-11| FDX| 217.94| -0.93| -0.42% | 

### Build/Run project

Program will monitor stocks daily. Append your list of stocks in tickers.txt

### APIs
yahoo-finance 1.4.0 : Python module to get stock data from Yahoo! Finance

```
pip install yahoo-finance
```

