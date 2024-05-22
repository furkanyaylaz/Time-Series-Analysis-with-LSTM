# Traffic Volume Forecasting Using LSTM

This project uses Long Short-Term Memory (LSTM) networks to forecast traffic volume based on hourly data.

## Overview

The goal of this project is to develop a model that can accurately predict traffic volume using time series data. The model is built using LSTM, a type of recurrent neural network (RNN) that is well-suited for time series forecasting.


## Data

The Metro Interstate Traffic Volume dataset contains hourly traffic volume data from the Minnesota Department of Transportation (DoT) ATR station 301, located between Minneapolis and St. Paul. This dataset includes hourly weather features and holiday information that impact traffic volume.

The dataset contains 48,204 records with the following 9 features:

1. **holiday**: Indicates whether the day is a holiday. If not, it is marked as 'None'.
2. **temp**: Temperature in Kelvin.
3. **rain_1h**: Amount of rain in the last hour in millimeters.
4. **snow_1h**: Amount of snow in the last hour in millimeters.
5. **clouds**: Percentage of cloud cover.
6. **weather_main**: Brief description of the main weather condition.
7. **weather_description**: Detailed description of the current weather condition.
8. **date_time**: Timestamp in 'Y/m/d H:M:S' format.
9. **traffic_volume**: Number of cars passing in the last hour.

The target feature in this dataset is the hourly traffic volume.



<!--## Results

The model's performance is evaluated using Mean Squared Error (MSE) on the test set. A plot of the actual vs. predicted values for the last 200 days is generated.

