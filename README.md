# Berkeley-Weather-Prediction
Contains ARIMAX, LSTM, and transformer models used for Weather Forecast SlackBot. Predicts min and max temperature daily, trained on 10 years worth of daily data from 2015 to 2024.

I completed this project in preparation for a tutorial I was leading for students joining the Data Science Society at Berkeley. The goal was to give an overview of time series prediction and deep learning methodologies to students without experience in those areas. 

## Notebooks
`arimax_min_temp`: Contains ARIMAX training to predict daily min temperature in Berkeley
`arimax_max_temp`: Contains ARIMAX training to predict daily max temperature in Berkeley
`lstm_minmax_temp`: Contains LSTM training & Bayesian finetuning to predict daily min & max temperature in Berkeley
`transformer_minmax_temp`: Contains transformer training & Bayesian finetuning to predict daily min & max temperature in Berkeley
