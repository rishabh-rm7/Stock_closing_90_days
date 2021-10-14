# Stock_closing_90_days
Following code fetches the last 90 days of closing stock prices of various companies given in excel file.

In first part i try to fetch to data from yahoo finance using pandas library pandas_datareader and its attribute yahoo finance.
but not all data comes under yahoo finance and it only get the data of 12 companies.

In second part I use NSEPY library and get_history attribute to fetch all 161 companies closing stocks.
