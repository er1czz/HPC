# Kaggle data challenge log
### 1. RMS Titanic Survival Prediction (testing water)
- Random forest classification, **accuracy** score 0.81930 for training and 0.77033 for testing
- Accuracy score: higher score is better, testing score provided by Kaggle
- to-do: Monte Carlo to simulate the missing data, especially passenger age.
### 2 Ames House Price Prediction (model fitting practice)
- Random forest regression, **RMLE** score 0.14319 for training and 0.18125 for testing 
- RMLE (Root Mean Squared Log Error): lower score is better, testing score provided by Kaggle
- to-do: exploratory data analysis and feature selection
### 3 IEEE-CIS Fraud Detection
<img src="https://github.com/er1czz/kaggle/blob/master/unsplash_transaction.JPG?raw=true" align = "left" style = "border:10px solid white">  

Credit card fraud is a common financial fraud that using a payment card to proceed a transaction with illegitimate nature. Researchers specialized in fraud dection often encouter this challenge: how to maximaize the transaction security with minimal hassles to clients. With the recent advance in machine learning and computation technology, this challenge can be addressed by implementing high accuracy fraud detection, which brings virtually no hassle to customers.       

This project intends to develop a predicative model based on machine learning algorithms in order to effectively detect fradulent transactions. Data are available on [Kaggle.com](https://www.kaggle.com/c/ieee-fraud-detection)  

[<b>Round 1</b>](https://github.com/er1czz/kaggle/blob/master/Fraud_Detection_fullset.ipynb): 
- Data preprocess
- Logistic, XGboost, Random Forest Classifications
- Issue: feature selection  

<b>Round 2 in progress ... </b>
- Aim to improve the practice of feature selection

# Misc
### Monte Carlo
- [MC calculation on Dice and Pi with Numpy Random](https://github.com/er1czz/kaggle/blob/master/Monte%20Carlo's%20Dice%20and%20Pi.ipynb)

#### Data Sources (Kaggle)  
1. https://www.kaggle.com/c/titanic  
2. https://www.kaggle.com/c/house-prices-advanced-regression-techniques  
3. https://www.kaggle.com/c/ieee-fraud-detection/  
