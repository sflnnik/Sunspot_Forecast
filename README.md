# Forecast of Monthly Sunspot numbers

## Description

This repository contains data and figures of Sunspot numbers monthly time series forecast.
Observational Sunspot data is provided by the World Data Center SILSO, Royal Observatory of Belgium, Brussels (https://www.sidc.be/silso/datafiles)
The forecast is estimated with a method based on a combination of numerical solution of nonlinear mean-field dynamo equations and two-layer artificial neural network.
The presented methodology is a continuous scientific work relying on several publications () 

## Repository directories
1) `data` contains ...
2) `figs` contains ...
3) `forecast` contains ...

## Data format

Format: Comma Separated values

Contents:
- Column 1-2: Gregorian calendar  Year-Month
- Column 3: predicted sunspot numbers 

### Actual forecast

![plot](./figs/2024/01/f_2024_01.png)

### ALatest monthly evaluated predictions and observations  `R`

![plot](./figs/2024/01/f_24_01.png)

### Comparison with the other methods of forecast

![plot](./figs/2024/01/f_2024_01_all.png)

