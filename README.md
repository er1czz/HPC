# Kaggle data challenge log
### 1. RMS Titanic Survival Prediction (testing water)
- Random forest classification, **accuracy** score 0.81930 for training and 0.77033 for testing
- Accuracy score: higher score is better, testing score provided by Kaggle
- to-do: Monte Carlo to simulate the missing data, especially passenger age.
### 2. Ames House Price Prediction (model fitting practice)
- Random forest regression, **RMLE** score 0.14319 for training and 0.18125 for testing 
- RMLE (Root Mean Squared Log Error): lower score is better, testing score provided by Kaggle
- to-do: exploratory data analysis and feature selection
### 3. IEEE-CIS Fraud Detection
<img src="https://github.com/er1czz/kaggle/blob/master/unsplash_transaction.JPG?raw=true" align = "left" style = "border:10px solid white">  

Credit card fraud is a common financial fraud that using a payment card to proceed a transaction with illegitimate nature. Researchers specialized in fraud dection often encouter such challenge: how to maximaize the transaction security with minimal hassles to clients. With the recent advance in machine learning and computation technology, this challenge can be addressed by implementing high accuracy fraud detection algorithms without bringing additional hassle to customers.       

This project intends to develop a predicative model based on machine learning algorithms. The goal is to maximize the detection rate of fradulent activities while minimizing the number of false alarms (false positive events).

[<b>Round 1</b>](https://github.com/er1czz/kaggle/blob/master/Fraud_Detection_fullset.ipynb): 
- Issue: feature selection  
- F<sub>1</sub> score 0.15 by XGboost model 
- F<sub>1</sub> score 0.29 by RandomForest model 
- F<sub>1</sub> score 0.15 by Logistic model 

[<b>Round 2</b>](https://github.com/er1czz/kaggle/blob/master/Fraud_Detection_fullset_2.ipynb):
- Improvement: feature selection
- F<sub>1</sub> score 0.94 by XGboost model 
- F<sub>1</sub> score 0.87 by RandomForest model 
- F<sub>1</sub> score 0.73 by Logistic model 

<b>Round 3</b> in progress ...
- Continue improving the predication accuracy using different data processing techniques (e.g. feature aggregation) 

## Data Sources (Kaggle)  
1. RMS Titanic Survival Prediction  https://www.kaggle.com/c/titanic  
2. Ames House Price Prediction https://www.kaggle.com/c/house-prices-advanced-regression-techniques  
3. IEEE-CIS Fraud Detection https://www.kaggle.com/c/ieee-fraud-detection/  

# Misc
### Monte Carlo
- [MC calculation on Dice and Pi with Numpy Random](https://github.com/er1czz/kaggle/blob/master/Monte%20Carlo's%20Dice%20and%20Pi.ipynb)
