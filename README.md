# Credit_Risk_Analysis

## Overview
Using data from a provide LoanStats_2019Q1.csv, I used RandomOverSampler and SMOTE, and undersample approaches as well as used the ClusterCentroids algorithm. Then, I used SMOTEENN  for a combination of those approaches. Lastly, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

## Results
I tried multiple approaches to machine learning for analysis:
 - Oversampling
 - SMOTE Oversampling
 - Undersampling
 - Combination (Over-and Undersampling)
 - Balanced Random Forest Classifier
 - Easy Ensemble AdaBoost Classifier
 
Below is an overview for the results from each.

### Oversampling
![oversampling](/Resources/oversampling_report.PNG)
 - Balance Accuracy Score: 0.6503
 - Precision: .99
 - Recall/Sensitivity: .61
 - F1: .75

### SMOTE Oversampling
![smote](/Resources/SMOTE_report.PNG)
 - Balance Accuracy Score: 0.6621
 - Precision: .99
 - Recall/Sensitivity: .69
 - F1: .81

### Undersampling
![undersampling](/Resources/undersampling_report.PNG)
 - Balance Accuracy Score: 0.5447
 - Precision: .99
 - Recall/Sensitivity: .40
 - F1: .56

### Combination (Over-and Undersampling)
![combo](/Resources/combo_report.PNG)
 - Balance Accuracy Score: 0.6774
 - Precision: .99
 - Recall/Sensitivity: .57
 - F1: .72

### Balanced Random Forest Classifier
![balance](/Resources/balance_random_forest_report.PNG)
 - Balance Accuracy Score: 0.7887
 - Precision: .99
 - Recall/Sensitivity: .87
 - F1: .93


### Easy Ensemble AdaBoost Classifier
![easy_ensemble_report](/Resources/easy_ensemble_report_report.PNG)
 - Balance Accuracy Score: 0.7887
 - Precision: .99
 - Recall/Sensitivity: .87
 - F1: .93


## Summary
After evaluating all of these approaches and algorithms, it seems that none of these would be appropriate to use since their precision score is almost perfect in every case. We seem to be overfitting, so these models would not be ideal to predict real world data.