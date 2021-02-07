# Credit_Risk_Analysis

## Analysis Overview 

This analysis aims to apply machine learning to a dataset from LendingClub to predict credit risk throughout the use of imbalanced-learn and scikit-learn libraries.

## Results 

Listed below are the balanced accuracy, precision, and recall scores of all six machine learning models.  

### The results from the Random Oversampler algorithm are:

  - Balanced accuracy score: 0.6743
  - Precision score: high_risk 0.01, low_risk 1.00 
  - Recall score: high_risk 0.74, low_risk 0.61 

### The results from the SMOTE Oversampling algorithm are:

  - Balanced accuracy score: 0.6623
  - Precision score: high_risk 0.01, low_risk 1.00 
  - Recall score: high_risk 0.63, low_risk 0.69
  
### The results from the ClusterCentroids algorithm are:

  - Balanced accuracy score: 0.6623
  - Precision score: high_risk 0.01, low_risk 1.00 
  - Recall score: high_risk 0.68, low_risk 0.41
  
 ### The results from the SMOTEENN algorithm are:
 
  - Balanced accuracy score: 0.5472
  - Precision score: high_risk 0.01, low_risk 1.00 
  - Recall score: high_risk 0.73, low_risk 0.59

 ### The results from the Balanced Random Forest Classifier are:
 
  - Balanced accuracy score: 0.7885
  - Precision score: high_risk 0.03, low_risk 1.00 
  - Recall score: high_risk 0.70, low_risk 0.87
  
 ### The results from the Easy Ensemble AdaBoost Classifier are:
 
  - Balanced accuracy score: 0.9317
  - Precision score: high_risk 0.09, low_risk 1.00 
  - Recall score: high_risk 0.92, low_risk 0.94
  
  ## Summary 
  
  A low precision is indicative of a large number of false positives, while a low recall is indicative of a large number of false negatives. Since our objective is to predict credit risk to minimize company loss, a high recall score is desired because we want to identify the clients that are high risk and will stop paying. Therefore, the goal is to have a small number of false negatives, indicated by a high recall score. 

In summary, the Easy Ensemble AdaBoost Classifier model seems like the best model at predicting credit risk because the model's accuracy is the highest of the six models, 0.9317, and the recall score, 0.92. Therefore, this model is good at finding positive high-risk clients. 
