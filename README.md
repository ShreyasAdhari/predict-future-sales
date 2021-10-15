# Predict-future-sales

--> Objective here is to predict the sales at a store for a particular item for a month.

--> Data is timeseries ( jan 2013 - oct 2015 ). The target month is nov 2015

--> lgbm_dataset notebook is used to preprocess dataset given and create new features.

--> hyperopt_lgbm notebook is used to train final model. The hyperparameters given were selected by bayesian optimisation. Optuna library was used.

--> Final rmse of 0.85295 was achieved.

![alt text](lb1.PNG)

--> Trained xgboost and catboost models as well.

--> Lightgbm model outperformed xgboost and catboost as well as ensembles of the models.


