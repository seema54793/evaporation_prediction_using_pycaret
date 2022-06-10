# evaporation_prediction_using_pycaret
```
PyCaret is an open-source, low-code machine learning library in Python that automates machine learning workflows. 
It is an end-to-end machine learning and model management tool that speeds up the experiment cycle exponentially
and makes you more productive.
```

PyCaret for Machine Learning.
## PyCaret is used for:
```
 ~Classification
 ~Regression
 ~Clustering
 ```
 
## Steps involved in this project:
```
~ Loading the Data via Pandas library
~ Cleaning the Data
~ Setting up the Environment, (and spliting the data into 80% training and 20% testing.)
~ Creating the model(regression)
~ Tune the model (automatically tune the hyperparameters of a regression model)
~ Ploting various model (analyze model performance using various plots)
~ Finalizing the model (by analysing the model with best value of r_square and RMSE score)
~ Predicting the model (make prediction on new / unseen data)
~ Saving or loading the model for future use.
```


# RESULTS:
```
## Testing performance of et
RMSE: 0.85
R2: 0.94
Testing performance of huber
RMSE: 1.06
R2: 0.90
Testing performance of catboost
RMSE: 0.51
R2: 0.98
Testing performance of xgboost
RMSE: 0.59
R2: 0.97
Testing performance of br
RMSE: 1.02
R2: 0.91
Testing performance of blender
RMSE: 0.77
R2: 0.95
```
------------------------------------------------------------
## Training performance of et
```
RMSE: 0.54
R2: 0.96
Training performance of catboost
RMSE: 0.49
R2: 0.97
Training performance of huber
RMSE: 0.69
R2: 0.94
Training performance of br
RMSE: 0.71
R2: 0.94
Training performance ofblender
RMSE: 0.46
R2: 0.97
Training performance of xgboost
RMSE: 0.33
R2: 0.99
```
```
et = extra tree regressor
br = Bayesian Ridge
In Blending I used Huber Regression,XGBoost Regreesion,Extra Tree Regressor and Bayesian Ridge Regressor
```

