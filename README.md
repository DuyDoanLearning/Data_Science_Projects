# Data Science Project
Welcome to my Data Science portfolio. I am Duy Doan, a postgraduate MSc in Financial Technology at the University of Nottingham, United Kingdom. This portfolio contains projects I have done while studying for my MSc degree. Please take a look, and if you want to connect with me, please reach me via my email at doanduy2705@gmail.com or my LinkedIn profile: https://www.linkedin.com/in/duyd/.

## [1. Machine Learning and Deep Learning: Explore the cointegration between global stock indices and commodities prices (MSc Dissertation Project)](https://github.com/DuyDoanLearning/stock_market_prediction_MachineLearning_and_LSTM.git)
* Downloaded data on Bloomberg from 2005 to 30/06/2023 for US & China stock indices, precious metal prices, exchange rates, and VN-Index (stock index of Vietnam) as the target variable.
* Performed EDA and selected meaningful features only.
* Performed Augmented Dickey-Fuller test for stationary and Granger's two-step methods to detect long-run relationships between variables. Performed Granger's causality test to select meaningful features further.
* Feed into ML models for regression task to evaluate how models perform on long-run relationship features in predicting prices through robust tests.
* Feed into LSTM models (univariate and multivariate) to evaluate DL models on exploring relevant features.

![](https://github.com/DuyDoanLearning/Data_Science_Projects/blob/main/results_img_technical_2.png)

## [2. CARAVAN Insurance Challenge - Kaggle Challenge](https://github.com/DuyDoanLearning/Caravan-Insurance-Challenge)

A Kaggle competition to build a model that best identifies potential customers who will likely purchase the CARAVAN insurance. The challenge of this problem is that the data was recorded manually with a lot of redundancy, and the relationship with the target variable is uncertain. The target label is also imbalanced (94% of label 0 and 6% of label 1).

In this case study, I prioritized recall scores to capture potential customers. The final model, Random Forests, achieved 82% overall accuracy with 80% recall. 

The full information about the challenge is presented here: https://www.kaggle.com/datasets/uciml/caravan-insurance-challenge.

![](https://github.com/DuyDoanLearning/Data_Science_Projects/blob/main/CARAVAN_challenge.png)
