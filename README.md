# Credit_Risk_Analysis

## Overview of Analysis 

The purpose of this analysis was to solve the challenge of credit card risk. The analysis will oversample the data using Random Over Sampler and SMOTE algorithms, undersample the data using Cluster Centroids algorithm and under and over sample the data using SMOTEENN algorithm. 

Then the analysis will compare the two machine learning models, Balanced Random Forest Classifier and Easy Ensemble Classified that reduce bias, to prisk. redict credit. 

## Results 

### Random Over Sampler

<img width="546" alt="Random Over Sampler" src="https://user-images.githubusercontent.com/68453460/108270325-4d5fcd80-713d-11eb-8fb4-80bcc90aed68.png">

* Balanced Accuracy Score of 64.7%
* High Risk: Precision of 1%, f1 score of 2% 
* Low Risk: Precision of 100%, f1 score of 71%

### SMOTE

<img width="549" alt="SMOTE" src="https://user-images.githubusercontent.com/68453460/108270327-4df86400-713d-11eb-845c-89c12ebd2314.png">

* Balanced Accuracy Score of 64.7%
* High Risk: Precision of 1%, f1 score of 2% 
* Low Risk: Precision of 100%, f1 score of 71%

### Cluster Centroids

<img width="552" alt="Cluster Centroids" src="https://user-images.githubusercontent.com/68453460/108270321-4d5fcd80-713d-11eb-996a-0e1d0dc2f0f5.png">

* Balanced Accuracy Score of 54.4%
* High Risk: Precision of 1%, f1 score of 1% 
* Low Risk: Precision of 100%, f1 score of 57%

### SMOTEENN

<img width="546" alt="SMOTEENN" src="https://user-images.githubusercontent.com/68453460/108270331-4df86400-713d-11eb-84f1-47dc4460914f.png">

* Balanced Accuracy Score of 64%
* High Risk: Precision of 1%, f1 score of 2% 
* Low Risk: Precision of 100%, f1 score of 73%

### Balance Random Forest Classifier 

<img width="561" alt="Balanced Random Forest Classifier" src="https://user-images.githubusercontent.com/68453460/108270317-4c2ea080-713d-11eb-9c1c-5d2f9b51f882.png">

* Balanced Accuracy Score of 76%
* High Risk: Precision of 3%, f1 score of 6% 
* Low Risk: Precision of 100%, f1 score of 94%

### Easy Ensemble Classified 

<img width="550" alt="Eaasy Ensemble Classified" src="https://user-images.githubusercontent.com/68453460/108270323-4d5fcd80-713d-11eb-9cad-215df2a4c20c.png">

* Balanced Accuracy Score of 93%
* High Risk: Precision of 9%, f1 score of 16% 
* Low Risk: Precision of 100%, f1 score of 97%

## Summary

The Cluster Centroid algorithm has the lowest accuracy score. Based on the analysis this would not an algorithm that would be recommended for use to determine credit risk. The Easy Ensemble Classified machine learning model has the highest accuracy and this would be the recommended model to use to determine credit risk.  
