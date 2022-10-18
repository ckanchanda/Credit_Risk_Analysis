# Credit_Risk_Analysis

## Overview 
The purpose of this analysis was to use various libraries and algorithims to build 
and evaluate machine learning models to predict credit risks. Models included:
* RandomOverSampler
* SMOTE
* ClusterCentroids
* SMOTEEN
* BalancedRandomForestClassifier
* EasyEnsembleClassifier

## Results

* Native Random Over Sampling results: 
	- Accuracy score: 64%
	- Precision score: 1%
	- Recall sore: 60%
![](Resources/randomoversampler.JPG)

* SMOTE
	- Accuracy score: 64%
	- Precision score: 1%
	- Recall sore: 60%
![](Resources/smote.JPG)

* ClusterCentroids
	- Accuracy score: 64%
	- Precision score: 1%
	- Recall sore: 60%
![](Resources/clustercentroids.JPG)

* SMOTEEN
	- Accuracy score: 64%
	- Precision score: 1%
	- Recall sore: 70%
![](Resources/SMOTEEN.JPG)

* BalancedRandomForestClassifier
	- Accuracy score: 76%
	- Precision score: 3%
	- Recall sore: 62%
![](Resources/BalancedRandomForestClassifier.JPG)

* EasyEnsembleClassifier
	- Accuracy score: 93%
	- Precision score: 9%
	- Recall sore: 92%
![](Resources/EasyEnsembleClassifier.JPG)

## Summary
After reviewing all six models, the EasyEnsembleClassifier proved the best model to use 
when analysizing credit risk. It returned the highest accuracy score of 93% and the 
highest recall/sensitivy score of 92%. 