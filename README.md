# Cirrhosis-Patient-Survival-Prediction

The dataset was generated from a deep learning model trained on the Cirrhosis Patient Survival Prediction dataset. 

We are dealing here with classification problem. Goal is to predict one of three classess. 

My approach uses LighGBM with BayesSearch for hyperparameters, and grid search for treshold ans dampling strategy.

Here is one of results:

Sampling: 2, Threshold: 0.05
Confusion Matrix:
[[854  64  75]
 [ 17  29   9]
 [127  55 351]]
              precision    recall  f1-score   support

           0       0.86      0.86      0.86       993
           1       0.20      0.53      0.29        55
           2       0.81      0.66      0.73       533

    accuracy                           0.78      1581
   macro avg       0.62      0.68      0.62      1581
weighted avg       0.82      0.78      0.79      1581
