# AirPollution_prediction
Predict air pollution around Eiffel Tower

This is the code for the machine learning project "Using Machine Learning models to predict air pollution around the Eiffel Tower" by [Adina Bondoc](mailto:adina-faye.bondoc@student-cs.fr) and [Jezuela Geg](mailto:jezuela.gega@student-cs.fr) as part of our Machine Learning course at Centrale Supelec, Paris Sacely, supervised by Tom Dupuis.

## Objective

The objective of this project is to develop and implement a series of predictive models using machine learning techniques, with a focus on forecasting the concentration of Nitrogen Dioxide (NO2) in the surrounding area of the Eiffel Tower using statistical models:
- ARIMA
- Prophet
- RNN
- LSTM

## Prerequisites

The code was run in Google Colab.

## How to run the code

The preprocessing is done in the [air-quality-cleaning.ipynb](./air-quality-cleaning.ipynb) notebook.

- To run ARIMA, please run the [stat-model.ipynb](./stat-model.ipynb) notebook.
- To run Prophet, please run the [prophet.ipynb](./prophet.ipynb) notebook.
- To run RNN models, please run the [rnn.ipynb](./rnn.ipynb) notebook.
- To run LSTM models:
-- For univariate models, run the [LSTM-univar.ipynb](./LSTM-univar.ipynb) notebook.
-- For multivariate models, run the [LSTM-multivar.ipynb](./LSTM-multivar.ipynb) notebook.
