# S&P 500 Changes

As a passive investor in the S&P 500, I tend to check the index around twice a day. When looking at the daily change, however, I never fully understood how much was 'a lot' and how much was 'a little'. I decided to create a tool that showed the user daily % change in the S&P 500 for a period of time of their choosing. 

The tool, having already downloaded data from [Yahoo Finance](https://finance.yahoo.com/quote/%5EGSPC/history?period1=-1325635200&period2=1612483200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true), converts it into a Pandas DataFrame, drops and cleans necessary columns, claculates daily % change, and then finds the median daily changes for days where the index gained, fell, and both. 

Below is a screenshot of a sample output. 

![screenshot](images/sample.png)