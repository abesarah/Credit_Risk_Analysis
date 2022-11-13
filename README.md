# Credit Risk Analysis
![ ](/Resources/nathan-dumlao-lvWw_G8tKsk-unsplash.jpg?raw=true=250x250)
### Purpose:
Using the credit card credit dataset, the data is oversampled using the RandomOverSampler and SMOTE algorithms, and undersampled using the ClusterCentroids algorithm. Then, a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, are used to predict credit risk. 

### Technologies Used: 
-	Python
    - Pandas
    - SciKit Learn
    
### [Deliverable 1](/credit_risk_resampling.ipynb)
- For all three algorithms, the following have been completed:
    - An accuracy score for the model is calculated
    - A confusion matrix has been generated
    - An imbalanced classification report has been generated 
    
### [Deliverable 2](/credit_risk_ensemble.ipynb)
- The BalancedRandomForestClassifier algorithm does the following:
    - An accuracy score for the model is calculated
    - A confusion matrix has been generated
    - An imbalanced classification report has been generated
    - The features are sorted in descending order by feature importance
    
- The EasyEnsembleClassifier algorithm does the following:
    - An accuracy score of the model is calculated
    - A confusion matrix has been generated
    - An imbalanced classification report has been generated
