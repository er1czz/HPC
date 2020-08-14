# Data challenge log
### 4. [Mercedes-Benz Greener Manufacturing](https://github.com/er1czz/data_challenges/blob/master/Mercedes_Manufacturing_v2.ipynb)
- Each assembled 
- How to reduce the testing time?  
<img src="https://github.com/er1czz/data_challenges/blob/master/car_740_480.jpg?raw=true" align = "right" alt="drawing" width="370"> 

<b>Situation</b>:  
- Each manufactured automobile needs to be tested to ensure the safety and reliability.  
- Testing is a time-consuming process     
- Different cars have different configurations/features  

<b>Task</b>:  
- Optimizing the speed of testing system using a algorithmic approach    

<b>Action</b>:  
- Using regression models to identify key features that affect the testing time.  

<b>Results</b>:  
- Regression models were applied to analyze the correlation between features and testing time  

<b>Takeaways</b>:  
- Key features were identified. Effort should be prioritized on optimizing those key features.  
- Top 3 features together require more than 40% time for testing, which are ID, X314, and X315.  
- Feature X314: took 35.8% testing time, about 36 seconds average.  

### 3. IEEE-CIS Fraud Detection
<img src="https://github.com/er1czz/data_challenges/blob/master/unsplash_transaction.JPG?raw=true" align = "right" style = "border:10px solid white">  

Credit card fraud is a common financial fraud. During pandemic, shopping everything online is the new norm. How to maximaize the transaction security with minimal hassles to clients? With the recent advance in machine learning and computation technology, this challenge can be addressed by implementing high accuracy predictive algorithms by machine learning.       

This project intends to develop a predicative model based on machine learning algorithms. The goal is to maximize the detection rate of fradulent activities while minimizing the number of false alarms (false positive events). To improve the model's performance, such as precision and recall, one need to consider the customers' need and how the decision affects the business. Large financial insititutes may perfer high recall model due to the large number of transactions, whereas small ones may emphasize on the model precision.

Business impact: 
- For fraud detection, both precision and recall need to be considered for evaluating model performance.
- High precision - less financial loss - favorable for small banking of limited number of transactions.
- High recall - less false flags - better user experience - favorable for large banking.

[<b> Latest Version 4</b>](https://github.com/er1czz/kaggle/blob/master/Fraud_Detection_fullset_4.ipynb)
- F<sub>1</sub> score 0.71 by XGBoost model
- F<sub>1</sub> score 0.60 by LightGBM model
- F<sub>1</sub> score 0.48 by RandomForest model 
- F<sub>1</sub> score 0.34 by Logistic model 
- Improvement: data normalization, model optimization

[<b>Post analysis on hyperparameters</b>](https://github.com/er1czz/kaggle/blob/master/XGB_opt.ipynb)   
Optimal settings:
- learning rate 0.1
- subsample \[0.5, 1\]
- n_estimater 1000  
- max_depth \[6, 9\]  
which are consisten with the best settings found in version 4 <b>(learning_rate=0.1, subsample=1.0 ,n_estimators=1000, max_depth=9)</b>.

Note:
- Due to the limit of computation power, the following computation-demanding actions are not performed, such as cross-validation, learning curve, and the fine tuning of model hyperparameters.

[<b>Version 3</b>](https://github.com/er1czz/kaggle/blob/master/Fraud_Detection_fullset_3.ipynb)   
- F<sub>1</sub> score 0.67 by XGBoost model
- F<sub>1</sub> score 0.60 by LightGBM model
- F<sub>1</sub> score 0.49 by RandomForest model 
- F<sub>1</sub> score 0.21 by Logistic model 
- Improvement: feature selection
- To do: model optimization, data normalization, learning curve, cross-validation

[<b>Version 2</b>](https://github.com/er1czz/kaggle/blob/master/Fraud_Detection_fullset_2.ipynb)
- F<sub>1</sub> score 0.70 by XGboost model 
- F<sub>1</sub> score 0.44 by RandomForest model 
- F<sub>1</sub> score 0.28 by Logistic model 
- Improvement: data cleaning
- To do: feature selection

[<b>Version 1</b>](https://github.com/er1czz/kaggle/blob/master/Fraud_Detection_fullset.ipynb)   
- F<sub>1</sub> score 0.15 by XGboost model 
- F<sub>1</sub> score 0.29 by RandomForest model 
- F<sub>1</sub> score 0.15 by Logistic model 
- To do: data cleaning, feature selection 
### 2. Ames House Price Prediction (model fitting practice) - [analysis](https://github.com/er1czz/kaggle/blob/master/House_prices_analysis.ipynb) - [regression](https://github.com/er1czz/kaggle/blob/master/House_prices_regression.ipynb)
- Random forest regression, **RMSE** score 0.14319 for training and 0.18125 for testing 
- RMLE (Root Mean Squared Log Error): lower score is better, testing score provided by Kaggle
- To do: exploratory data analysis and feature selection
### 1. RMS Titanic Survival Prediction (testing water) - [analysis](https://github.com/er1czz/kaggle/blob/master/Titanic_analysis.ipynb) - [classification](https://github.com/er1czz/kaggle/blob/master/Titanic_classifier.ipynb)
- Random forest classification, **accuracy** score 0.81930 for training and 0.77033 for testing
- Accuracy score: higher score is better, testing score provided by Kaggle
- To do: Monte Carlo to simulate the missing data, especially passenger age.

## Data Sources from Kaggle  
\(4\) Mercedes-Benz Greener Manufacturing  https://www.kaggle.com/c/mercedes-benz-greener-manufacturing  
\(3\) IEEE-CIS Fraud Detection https://www.kaggle.com/c/ieee-fraud-detection/  
\(2\) Ames House Price Prediction https://www.kaggle.com/c/house-prices-advanced-regression-techniques  
\(1\) RMS Titanic Survival Prediction  https://www.kaggle.com/c/titanic  

# Misc
### Monte Carlo
- [Monte Carlo calculation on Dice and Pi with Numpy Random](https://github.com/er1czz/kaggle/blob/master/Monte%20Carlo's%20Dice%20and%20Pi.ipynb)
