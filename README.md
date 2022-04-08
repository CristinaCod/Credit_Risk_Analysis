# Credit Risk Analysis
## Overview
### Purpose
This analysis was performed using our newly acquired knowledge of Machine Learning. Using started code provided in the form of a Python file, in our Jupyter Notebooks, we used different machine learning models to evaluate a dataset regarding credit and predicting high vs low risk. The models include oversampling techniques including **RandomOverSampler** and **SMOTE**. Undersampling using **ClusterCentroids**. Combination sampling using **SMOTTENN**. And finally using ensemble learners such as **BalancedRandomForestClassifier** and **EasyEnsembleClassifier**.

A snapshot of the initial features dataframe is provided below to show the start point for this analysis. However, please note this is not the entire dataframe and a few columns are missing from the end as they did not all fit on the screen.

![df.png](https://github.com/CristinaCod/Credit_Risk_Analysis/blob/main/Resources/Screen%20Shot%202022-04-08%20at%2011.58.15%20AM.png)

## Results
Below are the results of all six machine learning models used in this analysis. Here you will see the respected outputs for the balanced accuracy scores, confusion matrix, and imbalanced classification report for all six models. 

•	**RandomOverSampler Model**
![ros.png](https://github.com/CristinaCod/Credit_Risk_Analysis/blob/main/Resources/Screen%20Shot%202022-04-08%20at%2011.58.46%20AM.png)

The Balanced Accuracy Score is 64.9%.

The high risk precision is 1% with 62% sensitivity which gives us a harmonic mean, or F1 score, of 2%.

The low risk precision is 100% with 68% sensitivity.

•	**SMOTE Model**
![smote.png](https://github.com/CristinaCod/Credit_Risk_Analysis/blob/main/Resources/Screen%20Shot%202022-04-08%20at%2011.59.13%20AM.png)

Results are quite similar to the RandomOverSampler Model.

The Balanced Accuracy Score is 64.4%.

The high risk precision is 1% with 63% sensitivity which again gives us a harmonic mean, or F1 score, of 2%.

The low risk precision is 100% with 66% sensitivity.

•	**ClusterCentroids Model**
![ccm.png](https://github.com/CristinaCod/Credit_Risk_Analysis/blob/main/Resources/Screen%20Shot%202022-04-08%20at%2011.59.39%20AM.png)

The Balanced Accuracy Score is 64.4%.

The high risk precision is 1% with 61% sensitivity which again gives us a harmonic mean, or F1 score, of 2%.

The low risk precision is 100% with 45% sensitivity.

•	**SMOTEEN Model**
![smottenn.png](https://github.com/CristinaCod/Credit_Risk_Analysis/blob/main/Resources/Screen%20Shot%202022-04-08%20at%2012.00.04%20PM.png)

The Balanced Accuracy Score is 52.9%.

The high risk precision is 1% with 70% sensitivity which again gives us a harmonic mean, or F1 score, of 2%.

The low risk precision is 100% with 57% sensitivity.

•	**BalancedRandomForestClassifier Model**
![brfc.png](https://github.com/CristinaCod/Credit_Risk_Analysis/blob/main/Resources/Screen%20Shot%202022-04-08%20at%2012.00.43%20PM.png)

The Balanced Accuracy Score is 78.7%.

The high risk precision is 4% with 67% sensitivity which gives us a harmonic mean, or F1 score, of 7.5%.

The low risk precision is 100% with 91% sensitivity.

•	**EasyEnsembleClassifier Model**
![eec.png](https://github.com/CristinaCod/Credit_Risk_Analysis/blob/main/Resources/Screen%20Shot%202022-04-08%20at%2012.01.09%20PM.png)

The Balanced Accuracy Score is 92.5%.

The high risk precision is 7% with 91% sensitivity which gives us a harmonic mean, or F1 score, of 13%.

The low risk precision is 100% with 94% sensitivity.

## Summary
### Findings
When examining the precision for high-risk credit of the first four models seen in the resampling portion of this analysis, we see that they are very low and weak, being 1% for all of them. When we moved on to the last two models seen in the ensemble portion, the precision for high-risk credit did improve to 4% and 7%, respectfully. 

### Recommendations
The model where we saw the highest precision and balanced accuracy score was in the EasyEnsembleClassifier model. With a 93% BAS it detected virtually all high-risk credit which theoretically should make it the most reliable model to use. However, the amount of false positives, aka low risk credits improperly detected as high risk, cause us to be apprehensive in support of this model as well.

Additionally, while the EasyEnsembleClassfier model had the highest precision percentage of 7%, that is still low in the grand scheme of things. 
For these reasons it’s the best model to use if deemed absolutely necessary by the bank however, if not necessary then I would not recommend any of the models be used as it could reflect poorly on banks. 
