# Credit_Risk_Analysis 

## Overview
The purpose of this analysis is to use different techniques to evaluate models and unbalanced classes within credit risk.

## Results
The RandomOverSampler produced a balanced accuracy score of 0.646, a precision score of 0.99 and a recall score of 0.58.
The Smote produced a balanced accuracy score of 0.658, a precision score of 0.99 and a recall score of 0.68.
The ClusterCentroids produced a balanced accuracy score of 0.544, a precision score of 0.99 and a recall score of 0.40.
The Smoteenn produced a balanced accuracy score of 0.648, a precision score of 0.99 and a recall score of 0.57.
The BalancedRandomForestClassifier produced a balanced accuracy score of 0.788, a precision score of 0.99 and a recall score of 0.87.
The EasyEnsembleClassifier produced a balanced accuracy score of 0.915, a precision score of 0.99 and a recall score of 0.90.

## Summary
In conclusion, each model gave very accurate results. The EasyEnsembleClassifier model would be the model that I would suggest using in the future because it produced the highest accuracy score as well as the highest recall score, which means that most of their predictions were accurate. I would not use the Smoteenn model because their predictions were too split in half, causing the low balanced accuracy score and recall score. 
