# stocks-analysis
Performing analysis of the stock data for Steve. 
Practice

## Overview of Project
Steve has created an Excel file containing the stock date he wants us to analyze for his parents.
Results of analysis of Daqo stock showed that DQ dropped over 63% in 2018. So this company might not be 
the best option for Steve's parents to invest in. Now we want to analyze the entire stock market over the last few years to find 
some better choices for them.
In this analysis we are refactoring code to loop through all the data one time in order to collect the information we need. 
In order to do this we've used a tickerIndex variable and created three output arrays: tickerVolumes, tickerStartingPrices, and tickerEndingPrices to avoid nested loops.
Our refactore code should run faster than it did in our previous analysis for Steve.

## Results

### Now we want to compare the stock performance between 2017 and 2018
Resources\green_stocks_analysis_2017.png
Resources\green_stocks_analysis_2018.png
We made positive returns green and negative returns red. So it's easy to determine that 2017's stocks did well and 2018's wasn't as much successful.
Obviously Steve might recommend his parents to invest their funds to ENPH and RUN companies which returns were 81.9% and 84.0% respectively.

### Now we want to compare execution times of the original script and the refactored script
Elapsed run time for the original code for green stocks analysis (2017):
	Resources\green_stocks_2017.png
Elapsed run time for the refactored code for green stocks analysis (2017):
	Resources\VBA_Challenge_2017.png
Elapsed run time for the original code for green stocks analysis (2018):
	Resources\green_stocks_2018.png
Elapsed run time for the refactored code for green stocks analysis (2018):
	Resources\VBA_Challenge_2018.png
By comparing these screenshots we can conclude that our refactored code runs faster than original.

## Summary
All above showed us that the refactored code is more efficient. It runs faster than original.  It takes fewer steps and uses less memory. The script loops though all the data only one time in order to collect the information. 
In the future, Steve may want to perform his analysis on larger datasets with different companies tickers. So we will have to rewrite manually all this tickers. That would be good to add a code which could recognize and assign each of the new tickers to an element in the array. 
