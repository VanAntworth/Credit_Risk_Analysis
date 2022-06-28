# Credit_Risk_Analysis

Supervised Machine Learning and Credit Risk

Overview of the loan prediction risk analysis:

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. 

Employed different techniques to train and evaluate models with unbalanced classes. (Trained and tested 6 machine learning models)

 - RandomOverSampler
 - SMOTE
 - ClusterCentroids
 - SMOTEENN
 - BalancedRandomForestClassifier
 - EasyEnsembleClassifier


## Purpose:

To explain how a machine learning algorithm is used in data analytics.

Create training and test groups from a given data set.

Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.

Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.

Compare the advantages and disadvantages of each supervised learning algorithm.

Determine which supervised learning algorithm is best used for a given data set or scenario.

Use ensemble and resampling techniques to improve model performance.


# Results:

The balanced accuracy scores and the precision and recall scores of all six machine learning models are provided below for each of the 6 models that were run.

## Naive Random Oversampling

 Balanced Accuracy Score
 
    0.6567567513123915
 
 Precision:
 
    High_Risk: low  (.01)
    Low_Risk: high (1.0)
   
 Recall:
 
    High_Risk: .63
    Low_Risk:  .68
   
   
<img width="889" alt="Screen Shot 2022-06-28 at 3 40 12 PM" src="https://user-images.githubusercontent.com/99001393/176282930-a0f39c52-14b3-46d8-a071-d28dc839b2ad.png">


## SMOTE Oversampling

 Balanced Accuracy Score
 
    0.6254003650120261
 
  Precision:
    
    High_Risk: low  (.01)
    Low_Risk: high (1.0)
   
 Recall:
 
    High_Risk: .61
    Low_Risk:  .64
    
 <img width="851" alt="Screen Shot 2022-06-28 at 3 41 40 PM" src="https://user-images.githubusercontent.com/99001393/176283308-824ad7a4-d5e7-4f28-93ed-4991b68aa27a.png">

    
    
## Undersampling

 Balanced Accuracy Score
 
    0.6254003650120261
 
  Precision:
  
      High_Risk: low  (.01)
      Low_Risk: high (1.0)
      
 Recall:
 
    High_Risk: .61
    Low_Risk:  .64
    
 <img width="955" alt="Screen Shot 2022-06-28 at 3 41 51 PM" src="https://user-images.githubusercontent.com/99001393/176283426-8699e8d0-b593-4f93-b422-926a45570d0c.png">


## Combination Under-Over Sampling

 Balanced Accuracy Score
 
    0.6254003650120261
 
  Precision:
  
    High_Risk: low  (.01)
    Low_Risk: high (1.0)
    
 Recall:
 
    High_Risk: .60
    Low_Risk:  .46
    
<img width="1048" alt="Screen Shot 2022-06-28 at 3 42 22 PM" src="https://user-images.githubusercontent.com/99001393/176283599-0e18f945-766d-4071-a41b-07b6542fb837.png">

    

## Balanced Random Forest Classifier

 Balanced Accuracy Score
 
    0.7877672625306695
 
 Precision:
 
    High_Risk: low  (.04)
    Low_Risk: high (1.0)
    
 Recall:
 
    High_Risk: .67
    Low_Risk:  .91
    
    
   <img width="928" alt="Screen Shot 2022-06-28 at 3 43 43 PM" src="https://user-images.githubusercontent.com/99001393/176283996-317b63b2-9b39-4ff3-984e-15b23c4ae720.png">
  
 
## Easy Ensemble AdaBoost Classifier
 
 Balanced Accuracy Score
 
    0.925427358175101
 
 Precision:
 
    High_Risk: low  (.07)
    Low_Risk: high (1.0)
    
   
 Recall:
 
    High_Risk: .91
    Low_Risk: .94



<img width="952" alt="Screen Shot 2022-06-28 at 3 44 19 PM" src="https://user-images.githubusercontent.com/99001393/176284103-f4c97138-718f-4cee-980c-ea034bb6805d.png">



## Summary

In this challnege we used oversampling, undersampling , Combination (Over and Under) Sampling models as well as Ensemble Learners to find a best fitting algorithm to predict credit risk. This was an unbalanced classification problem, therefore many models were tested.

Easy Ensemble AdaBoost Classifier is shown to be the best machine learning model with a low risk recall score of .94. It would be the best model to choose for the credit card analysis.
