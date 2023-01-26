# stock-analysis

## Overview

The goal was to refactor our previous code to loop through all the data one time in order to collect the same information in a shorter amount of time (hopefully).

## Results

Many of the stocks had a positive return in 2017 while only TERP was in the red (barely) compared to a tough 2018 when only two stocks had positive returns.
Because we refactored the code to run through the data just once, we were able to cut the execution time by over a half. The time was still in the milliseconds, but much larger data sets can mean saving minutes or hours. 

## Summary

The advantage of refactoring code is that you already have completed the task and know the overall objective, so it just becomes a matter of rethinking a more efficient way to execute the plan. On the flip side, refactoring means tinkering which can lead to frustrating errors that can get a coder stuck.
The only reason I would prefer the original script is because it had fewer variables to keep track of. However, the refactored VBA code ran through the stock just once instead of 12 times for each ticker.
