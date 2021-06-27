# Institute_of_Data
Capstone Project uploaded as the final project in the Institute of Data 6 month Data Science and AI Part Time Course, December 2020 - May 2021. 

The project is investigating the Australian Road Toll for the years 1989 - 2021. The goal was to predict what the monthly road toll will be for the upcoming 12 months (April 2021 - April 2022.)

The work has been split across several notebooks and csv files at each stage of processing, in the following order:

1. MVA Capstone is the first notebook, involving wrangling the raw data. During visualisation, the file size became too large so it was split into;

2. mva_capstone_pp, which contains some pre-processing for further modelling. As I had chosen an LSTM model for time series analysis, I then changed tack with the data, output the df to a new csv;

3. mva_lstm contains the validation data from the initial stages of lstm modelling. Due to the way this data was initially structured, I used this data to validate whether I should use a 12, 24 or 48 month timestep window on my predictions. The 12 months seemed to fit the data the best;

4. mva_capstone_univariate_lstm_final contains the prediction data for the upcoming 12 months, with RMSE values used as the evaluation metric.


I have also provided a folder with the data visualisation that I used in my presentation and the presentation itself. 

All data was accessed from the Australian Road Deaths Database

https://data.gov.au/data/dataset/australian-road-deaths-database
