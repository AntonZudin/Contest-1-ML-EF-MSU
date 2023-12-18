# Contest-1-ML-EF-MSU


In this project we need to predict customers' medical insurance payments based on their personal data (age, sex, place of living, etc.) I used 3 ML models to tackle this problem: linear regression(and bagging of 3 linear regressions), Random Forest and MLP. I've chosen the first and the third model as there is 

Steps undertaken with linear regression, boosting and Random Forest  model:

* Encoding categorial features
* Hyperparameter tuning utilizing optuna library
* Cross Validation


Steps undertaken with MLP:
* Encoding categorial features
* Manual search for the best hyperparameters
* Splitting into train and test datasets
  


Conclusion: Predictions obtained from MLP were the most worthy on private score due to some linearity in the data.
