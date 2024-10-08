# Time Series Analysis and Forecasting for the Labor Market in Russia
## Project Description

This project is aimed at analyzing and forecasting time series data representing labor market indicators in the Russian Federation. 
The original dataset was collected from the EMISS website (Unified Interdepartmental Statistical Information System) 
and includes the following indicators:
* Average per capita monetary income
* Number of employed people (ages 15-72)
* Number of unemployed people (ages 15-72)

The data is analyzed for each of the eight federal districts:
1. cfo – Central Federal District,
2. szfo – North-Western Federal District,
3. ufo – Southern Federal District,
4. skfo – North Caucasian Federal District,
5. pfo – Volga Federal District,
6. uralfo – Ural Federal District,
7. sfo – Siberian Federal District,
8. dfo – Far Eastern Federal District.

## Datasets
Two main datasets were used for the analysis and forecasting:

1. Annual Data (from December 31, 2000, to December 31, 2022)
2. Quarterly Data (from Q1 2010 to Q4 2021)

### Annual Data
This dataset contains information at the end of each year and is used for building forecasting models with yearly frequency.

### Quarterly Data
This dataset includes quarterly data, allowing for a more detailed analysis of the indicators' changes throughout the year.

## Project Structure
### 1. Working with the Annual Dataset
The following files were developed for analyzing and forecasting time series based on annual data:

* TSPreparation – preliminary loading, processing, and analysis of the initial time series data.
* TS_model_ARIMA – implementation of the ARIMA model for time series forecasting.
* TS_model_Holt – implementation of Holt's exponential smoothing model for forecasting.
* TS_model_Prophet – implementation of the Prophet model for time series forecasting.

### 2. Working with the Quarterly Dataset
For analyzing and forecasting quarterly data, the following files were developed:

* TSPreparation(q) – preliminary loading, processing, and analysis of the initial time series data.
* TS_model_SARIMAX(q) – implementation of the SARIMAX model for forecasting quarterly data.
* TS_model_Holt-Winters(q) – use of Holt-Winters exponential smoothing model for forecasting.
* TS_model_Prophet(q) – implementation of the Prophet model for forecasting quarterly data.
* RNN Model – a Recurrent Neural Network model with two bidirectional LSTM layers will be implemented for forecasting.

## Libraries Used
The following main libraries were used in this project:
* pandas – for working with time series and tabular data.
* numpy – for performing numerical operations.
* matplotlib and seaborn – for data visualization.
* statsmodels – for building ARIMA and SARIMAX models.
* Prophet – for time series modeling.
* tensorflow/keras – for implementing Recurrent Neural Networks (RNN).

## Results
* Annual Data:
  * Forecasting was performed using ARIMA, Holt, and Prophet models.
* Quarterly Data:
  * Forecasting was done using SARIMAX, Holt-Winters, and Prophet models.
  * An RNN model with bidirectional LSTM layers will be added in the future.

## Contacts
If you have any questions about the project, feel free to reach out to me:

* Email: ---
* GitHub: ---
