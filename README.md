# Data_Science_Projects
This repository is where I put my Data Science projects while doing my MSc Fintech at the University of Nottingham.

## [1. Machine Learning and Deep Learning: Explore the cointegration between global stock indices and commodities prices (MSc Dissertation Project)](https://github.com/DuyDoanLearning/stock_market_prediction_MachineLearning_and_LSTM.git)
* Downloaded data on Bloomberg from 2005 to 30/06/2023 for US & China stock indices, precious metal prices, exchange rates, and VN-Index (stock index of Vietnam) as the target variable.
* Performed EDA and selected meaningful features only.
* Performed Augmented Dickey-Fuller test for stationary and Granger's two-step methods to detect long-run relationships between variables. Performed Granger's causality test to select meaningful features further.
* Feed into ML models for regression task to evaluate how models perform on long-run relationship features in predicting prices through robust tests.
* Feed into LSTM models (univariate and multivariate) to evaluate DL models on exploring relevant features.
![Result of predictions](https://github.com/DuyDoanLearning/stock_market_prediction_MachineLearning_and_LSTM/blob/Stock-Prediction/Images/results_img_lag%20only_closer.png)
