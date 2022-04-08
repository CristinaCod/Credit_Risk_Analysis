# Credit Risk Analysis
## Overview
### Purpose


A snapshot of the initial features dataframe is provided below to show the start point for this analysis. However, please note this is not the entire dataframe and a few columns are missing from the end as they did not all fit on the screen.

![df.png](https://github.com/CristinaCod/Credit_Risk_Analysis/blob/main/Resources/Screen%20Shot%202022-04-08%20at%2011.58.15%20AM.png)

## Results
Below are the results of all six machine learning models used in this analysis. Here you will see the respected outputs for the balanced accuracy scores, confusion matrix, and imbalanced classification report for all six models. 

•	**RandomOverSampler Model**
![ros.png](https://github.com/CristinaCod/Credit_Risk_Analysis/blob/main/Resources/Screen%20Shot%202022-04-08%20at%2011.58.46%20AM.png)

The Balanced Accuracy Score is 64.9%.

The high risk precision is 1% with 62% sensitivity which gives us a harmonic mean, or F1 score, of 2%.

•	**SMOTE Model**
![smote.png](https://github.com/CristinaCod/Credit_Risk_Analysis/blob/main/Resources/Screen%20Shot%202022-04-08%20at%2011.59.13%20AM.png)

Results are quite similar to the RandomOverSampler Model.

The Balanced Accuracy Score is 64.4%.

The high risk precision is 1% with 63% sensitivity which again gives us a harmonic mean, or F1 score, of 2%.

•	**ClusterCentroids Model**
![ccm.png](https://github.com/CristinaCod/Credit_Risk_Analysis/blob/main/Resources/Screen%20Shot%202022-04-08%20at%2011.59.39%20AM.png)

The Balanced Accuracy Score is 64.4%.

The high risk precision is 1% with 61% sensitivity which again gives us a harmonic mean, or F1 score, of %.

•	**SMOTEEN Model**
![smottenn.png](https://github.com/CristinaCod/Credit_Risk_Analysis/blob/main/Resources/Screen%20Shot%202022-04-08%20at%2012.00.04%20PM.png)

The Balanced Accuracy Score is 52.9%.

The high risk precision is 1% with 70% sensitivity which again gives us a harmonic mean, or F1 score, of %.

•	**BalancedRandomForestClassifier Model**
![brfc.png](https://github.com/CristinaCod/Credit_Risk_Analysis/blob/main/Resources/Screen%20Shot%202022-04-08%20at%2012.00.43%20PM.png)

The Balanced Accuracy Score is 78.7%.

The high risk precision is 4% with 67% sensitivity which again gives us a harmonic mean, or F1 score, of 7%.

•	**EasyEnsembleClassifier Model**
![eec.png](https://github.com/CristinaCod/Credit_Risk_Analysis/blob/main/Resources/Screen%20Shot%202022-04-08%20at%2012.01.09%20PM.png)

The Balanced Accuracy Score is 92.5%.

The high risk precision is 7% with 91% sensitivity which again gives us a harmonic mean, or F1 score, of 14%.

## Summary
### Findings

### Recommendations
