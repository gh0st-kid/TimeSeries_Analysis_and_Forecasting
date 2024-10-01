# Time Seriese Project

This project was prepared and implemented for a master's thesis on the analysis of time series characterizing the labor market in the Russian Federation.

The original dataset was formed from data collected from the Rosstat website. The following indicators were used in this scientific research: 
* Average per capita monetary income
* The number of employed people aged 15-72 years
* The number of unemployed people aged 15-72 years

These data were collected for each of the eight federal districts:
1. cfo – Central Federal District,
2. szfo – North-Western Federal District,
3. ufo – Southern Federal District,
4. skfo – North Caucasian Federal District,
5. pfo – Volga Federal District,
6. uralfo – Ural Federal District,
7. sfo – Siberian Federal District,
8. dfo – Far Eastern Federal District.

The year column contains information about timestamps, the year to
which the feature observation belongs, and it will also be used
as an index column.

An initial analysis of the prepared time series was carried out and the following models were implemented: 
* ARIMA
* Exponential Holt smoothing
* Prophet (https://github.com/facebook/prophet)
* RNN model with two bidirectional LSTM layers.
