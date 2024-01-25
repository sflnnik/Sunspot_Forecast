# SolarActivityPrediction

### Description

This repository contains data of solar activity forecast. 
Data are obtained using a method based on a combination of the numerical solution of the nonlinear mean-field dynamo equations and the artificial neural network.
The detail can be found in the paper (https://doi.org/10.1017/S0022377818000600, PDF-file  in the `doc/` folder).

### Data format
We update our forecast of 13-months running averaged sunspot numbers at the beginning of each month.
The files `predict_YY_MM.csv`appear in the `data/` folder.

Format: Comma Separated values

Contents:
- Column 1-2: Gregorian calendar  Year-Month
- Column 3: predicted sunspot numbers 

### Specific time intervals

| Date period    |      Reference  |
|----------------|----------|
|1997/01—2017/10 | tuning methodology |
|2017/11—2021/09 | monthly forecast for testing |
|2021/10—        | monthly forecast during the project |

## Prediction Accuracy Analysis (plots)
We compare our forecast with observational data provided by https://www.sidc.be/silso/datafiles
(`SN_ms_tot_V2.0.csv` is available in the `doc/` folder).

* Actual forecast

![plot](./figs/2024/01/f_2024_01.svg)

* Latest monthly evaluated predictions and observations  `R`

![plot](./figs/2024/01/f_24_01.png)

* Comparison with the other methods of forecast

![plot](./figs/2024/01/f_2024_01_all.svg)

