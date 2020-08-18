# Data challenge log
## 4. Mercedes-Benz Greener Manufacturing - [a regression problem and its solution](https://github.com/er1czz/data_challenges/blob/master/Mercedes_Manufacturing_v3.ipynb)
<img src="https://github.com/er1czz/data_challenges/blob/master/car_740_480.jpg?raw=true" align = "right" alt="drawing" width="300"> 

<b>Situation</b>:  
- Assembled automobiles need to be tested to ensure the safety and reliability.  
- Testing is a time-consuming process.     
- Different cars have different configurations/features.  

<b>Task</b>: how to cut the testing time using a algorithmic approach?    

<b>Action</b>: using regression models to identify key features that affect the testing time.  

<b>Results</b>: regression models were applied to analyze the correlation between features and testing time.  

<b>Takeaways</b>:  
- Key features were identified. Effort should be prioritized on optimizing those key features.  
- Top 3 features together require more than 40% time for testing, which are ID, X314, and X315.  
- Feature X314: took 35.8% testing time, about 36 seconds average.  

## 3. IEEE-CIS Fraud Detection - [a classification problem and its solution](https://github.com/er1czz/kaggle/blob/master/Fraud_Detection_fullset_4.ipynb)
<img src="https://github.com/er1czz/data_challenges/blob/master/unsplash_transaction.JPG?raw=true" align = "right" style = "border:10px solid white">  

<b>Situation</b>:
- Credit card fraud is a common financial fraud, especially during pandemic.
- Shopping everything online is the new norm.

<b>Task</b>: how to maximaize the transaction security with minimal hassles to clients?

<b>Action</b>: developing a predicative model based on machine learning algorithms of binary classification.

<b>Results</b>: maximized the detection rate of fradulent activities while minimizing the number of false alarms (false positive events).

<b>Takeaways</b>: 
- For fraud detection, both precision and recall need to be considered for evaluating model performance.
- High precision - less financial loss - favorable for small banking of limited number of transactions.
- High recall - less false flags - better user experience - favorable for large banking.

[<b> Version 4</b>](https://github.com/er1czz/kaggle/blob/master/Fraud_Detection_fullset_4.ipynb) <b>(<em>Latest</em>)</b> and [<b>corresponding hyperparameter analysis</b>](https://github.com/er1czz/kaggle/blob/master/XGB_opt.ipynb)  
- Improvement: data normalization, model optimization   
- Note: due to the large size of data set, computation-demanding actions are not performed including cross-validation, learning curve, and the fine tuning of model hyperparameters.

<b> Previous versions:</b>  
[Version 3](https://github.com/er1czz/kaggle/blob/master/Fraud_Detection_fullset_3.ipynb)   
- Improvement: feature selection
- To do: model optimization, data normalization, learning curve, cross-validation

[Version 2](https://github.com/er1czz/kaggle/blob/master/Fraud_Detection_fullset_2.ipynb)
- Improvement: data cleaning
- To do: feature selection

[Version 1](https://github.com/er1czz/kaggle/blob/master/Fraud_Detection_fullset.ipynb)   
- To do: data cleaning, feature selection 
## 2. Ames House Price Prediction (model fitting practice) - [analysis](https://github.com/er1czz/kaggle/blob/master/House_prices_analysis.ipynb) - [regression](https://github.com/er1czz/kaggle/blob/master/House_prices_regression.ipynb)
- Random forest regression, **RMSE** score 0.18125.   
- RMSE (Root Mean Squared Error): lower score is better, testing score provided by Kaggle.  
- To do: exploratory data analysis and feature selection
## 1. RMS Titanic Survival Prediction (testing water) - [analysis](https://github.com/er1czz/kaggle/blob/master/Titanic_analysis.ipynb) - [classification](https://github.com/er1czz/kaggle/blob/master/Titanic_classifier.ipynb)
- Random forest classification, **accuracy** score 0.77033.  
- Accuracy score: higher score is better, testing score provided by Kaggle.  
- To do: Monte Carlo to simulate the missing data, especially passenger age.

## Sources:
**Data sets from kaggle.com**  
- \(4\) Mercedes-Benz Greener Manufacturing  https://www.kaggle.com/c/mercedes-benz-greener-manufacturing  
- \(3\) IEEE-CIS Fraud Detection https://www.kaggle.com/c/ieee-fraud-detection/  
- \(2\) Ames House Price Prediction https://www.kaggle.com/c/house-prices-advanced-regression-techniques  
- \(1\) RMS Titanic Survival Prediction  https://www.kaggle.com/c/titanic   

**Stock Photos from unsplash.com**  
- Car assembly line by Lenny Kuhne: https://unsplash.com/photos/jHZ70nRk7Ns
- Business Man with a credit card by rupixen https://unsplash.com/photos/Q59HmzK38eQ

# Misc 
- [Monte Carlo calculation on Dice and Pi with Numpy Random](https://github.com/er1czz/kaggle/blob/master/Monte%20Carlo's%20Dice%20and%20Pi.ipynb)  
- [Common packages for data challenges](https://github.com/er1czz/data_challenges/blob/master/install-packages.ipynb)
