# ASX stock Analaysis 

In this project I am going to analyze, how Top companies in each sector listed on ASX stock market have performed since Jan 2019.   

## Background 

Covid 19 pandemic started in Australia on Jan 2020. 
As we all know, Time of Covid 19 was of extreme uncertaintly. 

Australian borders were closed to all non-residents. Social distancing rules were imposed and all "non-essential" services were closed. The federal government announced an economic stimulus packages to combat the effects of coronavirus on the economy. Reserve Bank of Australia slashed the Cash rate and started Quantitative Easing to boost the Economy. 

## Purpose of analysis
For my analysis I have selected top company by market cap from each sector listed on the ASX Stock exchange.
The analysis will look at 2019 prices of the selected companies and compare them against 2020 and 2021. 


## Prerequisite
⦁ ASX list of companies
  I downloaded all ASX listed companies from https://www2.asx.com.au/markets/trade-our-cash-market/directory
  I sorted the list on Sector and Market Cap.
  
⦁ Selenium Webdriver 

⦁ Selenium edge service for Microsoft Edge.

⦁ numpy

⦁ Pandas 

⦁ Beautifulsoup 

⦁ time series 

⦁ OS Path

⦁ matplotlib

## Methodology 
Download ASX price data from Yahoo. 
⦁ Navigate to Yahoo finanance https://au.finance.yahoo.com/ 
⦁ Type in any ASX ticker in the search box e.g. CBA.AX (Note: All Australian Ticker end with .AX) 
⦁ Click on Historical data and choose date range. I used 01 Jan 2019 - 31 Mar 2022 
⦁ This address can be used for automation. Just need to replace CBA.AX with tickers for respective comapny.

## Price Data Analysis 
Data from 1 Jan 2019 to 31 Dec 2019 will be considered Pre Covid
To compare share price data, I will be using Adj. close price. 
Adj. close price is calculated after taking into consideration the corporate action events such as stock split, dividents etc. 

## Data Analysis Objective 
I will try to analyse if Covid 19 impact on Top companies of each sector listed on ASX Stock Exchange.
