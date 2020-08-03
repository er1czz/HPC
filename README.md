# Kaggle data challenge log
### 1. RMS Titanic Survival Prediction (testing water) - [analysis](https://github.com/er1czz/kaggle/blob/master/Titanic_analysis.ipynb) - [classification](https://github.com/er1czz/kaggle/blob/master/Titanic_classifier.ipynb)
- Random forest classification, **accuracy** score 0.81930 for training and 0.77033 for testing
- Accuracy score: higher score is better, testing score provided by Kaggle
- to-do: Monte Carlo to simulate the missing data, especially passenger age.
### 2. Ames House Price Prediction (model fitting practice) - [analysis](https://github.com/er1czz/kaggle/blob/master/House_prices_analysis.ipynb) - [regression](https://github.com/er1czz/kaggle/blob/master/House_prices_regression.ipynb)
- Random forest regression, **RMLE** score 0.14319 for training and 0.18125 for testing 
- RMLE (Root Mean Squared Log Error): lower score is better, testing score provided by Kaggle
- to-do: exploratory data analysis and feature selection
### 3. IEEE-CIS Fraud Detection
<img src="https://github.com/er1czz/kaggle/blob/master/unsplash_transaction.JPG?raw=true" align = "right" style = "border:10px solid white">  

Credit card fraud is a common financial fraud that using a payment card to proceed a transaction with illegitimate nature. Researchers specialized in fraud dection often encouter such challenge: how to maximaize the transaction security with minimal hassles to clients. With the recent advance in machine learning and computation technology, this challenge can be addressed by implementing high accuracy fraud detection algorithms without bringing additional hassle to customers.       

This project intends to develop a predicative model based on machine learning algorithms. The goal is to maximize the detection rate of fradulent activities while minimizing the number of false alarms (false positive events).

[<b>Round 1</b>](https://github.com/er1czz/kaggle/blob/master/Fraud_Detection_fullset.ipynb):  
- F<sub>1</sub> score 0.15 by XGboost model 
- F<sub>1</sub> score 0.29 by RandomForest model 
- F<sub>1</sub> score 0.15 by Logistic model 
- To do: data cleaning, feature selection 

[<b>Round 2</b>](https://github.com/er1czz/kaggle/blob/master/Fraud_Detection_fullset_2.ipynb):
- F<sub>1</sub> score 0.70 by XGboost model 
- F<sub>1</sub> score 0.44 by RandomForest model 
- F<sub>1</sub> score 0.28 by Logistic model 
- Improvement: data cleaning
- To do: feature selection

[<b>Round 3</b>](https://github.com/er1czz/kaggle/blob/master/Fraud_Detection_fullset_3.ipynb)   
- F<sub>1</sub> score 0.62 by LightGBM model
- F<sub>1</sub> score 0.61 by XGBoost model
- F<sub>1</sub> score 0.48 by RandomForest model 
- F<sub>1</sub> score 0.19 by Logistic model 
- Improvement: feature selection based on importances
- To do: model optimization, data normalization

<b> Round 4</b> in progress

## Data Sources from Kaggle  
1. RMS Titanic Survival Prediction  https://www.kaggle.com/c/titanic  
2. Ames House Price Prediction https://www.kaggle.com/c/house-prices-advanced-regression-techniques  
3. IEEE-CIS Fraud Detection https://www.kaggle.com/c/ieee-fraud-detection/  

# Misc
### Monte Carlo
- [Monte Carlo calculation on Dice and Pi with Numpy Random](https://github.com/er1czz/kaggle/blob/master/Monte%20Carlo's%20Dice%20and%20Pi.ipynb)
