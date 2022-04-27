# Credit_Risk_Analysis

## Overview

The purpose of this project is to solve credit card risk using data preparation, statistical reasoning and machine learning.

The data is from credit card credit dataset from LendingClub, a peer-to-peer lending services company.
The methods are oversampling using the RandomOverSampler and SMOTE algorithms, undersampling using the ClusterCentroids algorithm, and combination of over and undersampling using the SMOTEENN algorithm. 
We will then compare BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 


## Results

## Naive Random Oversampling

Model Accuracy 

!["images/01_NaiveRandom2.png"](https://github.com/Williamj83/Credit_Risk_Analysis/blob/main/images/Naive_Random.png)


## SMOTE Oversampling

Model Accuracy 

!["images/02_SMOTE2.png"](https://github.com/Williamj83/Credit_Risk_Analysis/blob/main/images/Smote.png)


## Undersampling

Model Accuracy 
!["images/03_UnderSamp2.png"](https://github.com/Williamj83/Credit_Risk_Analysis/blob/main/images/Undersampling.png)


## Combination (Over and Under) Sampling

Model Accuracy 

!["images/04_Combi2.png"](https://github.com/Williamj83/Credit_Risk_Analysis/blob/main/images/Combination.png)


## Balanced Random Forest Classifier

Model Accuracy 

!["images/05_RandomForest2.png"](https://github.com/Williamj83/Credit_Risk_Analysis/blob/main/images/Balanced_random.png)


## Easy Ensemble AdaBoost Classifier

Model Accuracy 

!["images/06_AdaBoost2.png"](https://github.com/Williamj83/Credit_Risk_Analysis/blob/main/images/easy_ensemble.png)


## Summary

**Easy Ensemble AdaBoost Classifier** produced the best result when predicting high risk credit applications with a 0.93 accuracy and a 0.92 recall score.
