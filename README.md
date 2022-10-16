# Credit_Risk_Analysis
## Using Machine Learning

# Overview
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. We will use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. We compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.  We will evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.


# Resuls

## Naive Random Oversampling
-	Balanced Accuracy Score 66%
-	Precision high risk score 1% low risk score 100%
-	Recall score for high risk 66% low risk 67%

## SMOTE Oversampling
-	The Balanced Accuracy Score is 66% against 
-	Precision high risk score is only 1% and low risk score is 100%
-	Recall score for high risk is at 62% and low risk at 64%

## Undersampling Cluster Centroids Algorithm
-	The Balanced Accuracy Score is 63%
-	Precision high risk score 1% and low risk score is 100%
-	Recall score for high risk 61% and low risk 65%

## SMOTEENN Model
-	The Balanced Accuracy Score is 52%
-	Precision high risk score 1% and low risk score 100%
-	Recall score for high risk 70% and low risk 57%

## Balanced Random Forest Classifier
-	The Balanced Accuracy Score is at 82%
-	Precision high risk score is 4% and low risk score is 100%
-	Recall score for high risk is at 72% and low risk at 91%

## Easy Ensemble AdaBoost Classifier
-	The Balanced Accuracy Score is at 91%
-	Precision high risk score is 7% and low risk score is 100%
-	Recall score for high risk is at 90% and low risk at 94%

# SUMMARY
The Balanced Accuracy Score of 91% is shown by EasyEnsembleClassifier with measures the ability to detect high risk credit scores & low risk scores. Therefore, this model can highly be recommended. There is a deficiency of precision in other models used to perform Credit risk analysis compared to EasyEnsembleClassifier.

