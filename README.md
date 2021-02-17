# Credit_Risk_Analysis

## Overview of Analysis 

The purpose of this analysis was to solve the challenge of credit card risk. The analysis will oversample the data using Random Over Sampler and SMOTE algorithms, undersample the data using Cluster Centroids algorithm and under and over sample the data using SMOTEENN algorithm. 

Then the analysis will compare the two machine learning models, Balanced Random Forest Classifier and Easy Ensemble Classified that reduce bias, to prisk. redict credit. 

## Results 

### Random Over Sampler

* Balanced Accuracy Score of 64.7%
* High Risk: Precision of 1%, f1 score of 2% 
* Low Risk: Precision of 100%, f1 score of 71%

### SMOTE

* Balanced Accuracy Score of 64.7%
* High Risk: Precision of 1%, f1 score of 2% 
* Low Risk: Precision of 100%, f1 score of 71%

### Cluster Centroids

* Balanced Accuracy Score of 54.4%
* High Risk: Precision of 1%, f1 score of 1% 
* Low Risk: Precision of 100%, f1 score of 57%

### SMOTEENN

* Balanced Accuracy Score of 64%
* High Risk: Precision of 1%, f1 score of 2% 
* Low Risk: Precision of 100%, f1 score of 73%

### Balance Random Forest Classifier 

* Balanced Accuracy Score of 76%
* High Risk: Precision of 3%, f1 score of 6% 
* Low Risk: Precision of 100%, f1 score of 94%

### Easy Ensemble Classified 

* Balanced Accuracy Score of 93%
* High Risk: Precision of 9%, f1 score of 16% 
* Low Risk: Precision of 100%, f1 score of 97%

## Summary

The Cluster Centroid algorithm has the lowest accuracy score. Based on the analysis this would not an algorithm that would be recommended for use to determine credit risk. The Easy Ensemble Classified machine learning model has the highest accuracy and this would be the recommended model to use to determine credit risk.  