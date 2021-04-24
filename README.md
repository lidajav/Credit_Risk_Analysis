# Credit_Risk_Analysis

## Overview

This project uses different techniques to train and avaluate models with unblanced classes using credit card dataset.
In this analysis we use the following models for our evaluation:

- Oversampling ( RandomOverSampler and SMOTE algorithms)
- Undersampling ClusterCentroids algorithm)
- Combinational approach(SMOTEENN algorithm)
- Two machine learning models that reduces bias to predit credit risk( BalancedRandomForestClassifier and EasyEnsembleClassifier)


## Result

- RandomOverSampler Model:

The accuracy score for this model is 63.75%. The average precision and recall was 99% and 67%. Below is the confusion matrix and classification reports for this model. The precison for high risk is low at 1%, same as f1 score at  2% for this class. That means we have a large number of false positive or large number of low risk creit cards that predicted high risk.The recall for high risk is 61%.

![Confusion matrix](Naive_ran_samp_cm.png)

![Classification Report](Naive_ran_samp_report.png)

- SMOTE Oversamling:

The accuracy for this model is 64.70%.The average precision and recall was 99% and 64%. Below is the confusion matrix and classification reports for this model. The precison for high risk is low at 1%, same as f1 score at 2% for this class. That means we have a large number of false positive or large number of low risk creit cards that predicted high risk.The recall for high risk is 66%.

![Confusion matrix](Smote_cm.png)

![Classification Report](Smote_report.png)

- Undersampling

The accuracy score for this model is 52.96%. The average precision and recall was 99% and 45%. Below is the confusion matrix and classification reports for this model. The precison for high risk is low at 1%, same as f1 score at 1% for this class. That means we have a large number of false positive or large number of low risk creit cards that predicted high risk.The recall for high risk is 61%. 

![Confusion matrix](Undersampling_cm.png)

![Classification Report](Undersampling_report.png)


- Combination (Over and Under) Sampling:

The accuracy for this model is 64.04%.The average precision and recall was 99% and 58%. Below is the confusion matrix and classification reports for this model. The precison for high risk is low at 1%, same as f1 score at 2% for this class. That means we have a large number of false positive or large number of low risk creit cards that predicted high risk.The recall for high risk is 70%.

![Confusion matrix](Combination_cm.png)

![Classification Report](Combination_report.png)

- 


## Summary