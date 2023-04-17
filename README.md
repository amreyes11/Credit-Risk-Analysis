# Credit-Risk-Analysis




DELIVERABLES

This new assignment consists of three technical analysis deliverables and a written report.

Deliverable 1: Use Resampling Models to Predict Credit Risk
Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
Deliverable 4: A Written Report on the Credit Risk Analysis README.md


Deliverable 1: Use Resampling Models to Predict Credit Risk

Using your knowledge of the imbalanced-learn and scikit-learn libraries, you’ll evaluate three machine learning models by using resampling to determine which is better at predicting credit risk. First, you’ll use the oversampling RandomOverSampler and SMOTE algorithms, and then you’ll use the undersampling ClusterCentroids algorithm. Using these algorithms, you’ll resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

For all three algorithms, the following have been completed:
  * An accuracy score for the model is calculated 
  * A confusion matrix has been generated 
  * An imbalanced classification report has been generated


Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk

Using your knowledge of the imbalanced-learn and scikit-learn libraries, you’ll use a combinatorial approach of over- and undersampling with the SMOTEENN algorithm to determine if the results from the combinatorial approach are better at predicting credit risk than the resampling algorithms from Deliverable 1. Using the SMOTEENN algorithm, you’ll resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

The combinatorial SMOTEENN algorithm does the following:
  * An accuracy score for the model is calculated 
  * A confusion matrix has been generated 
  * An imbalanced classification report has been generated 

Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

Using your knowledge of the imblearn.ensemble library, you’ll train and compare two different ensemble classifiers, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk and evaluate each model. Using both algorithms, you’ll resample the dataset, view the count of the target classes, train the ensemble classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

The BalancedRandomForestClassifier algorithm does the following:

  * An accuracy score for the model is calculated 
  * A confusion matrix has been generated 
  * An imbalanced classification report has been generated 
  * The features are sorted in descending order by feature importance 
  
The EasyEnsembleClassifier algorithm does the following:

  * An accuracy score of the model is calculated 
  * A confusion matrix has been generated 
  * An imbalanced classification report has been generated 


Deliverable 4: Written Report on the Credit Risk Analysis


DELIVERABLE RESULTS:  See below.  

Below are the results used for predictive modeling for High-Risk loans.

Random Oversampling: 

<img width="887" alt="Naive Random Oversampling" src="https://user-images.githubusercontent.com/119356418/232605805-799387ae-ded5-47b6-9984-9841ba65fdc0.png">

SMOTE:

<img width="914" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/119356418/232605842-377562aa-fb1c-4cc2-b534-76f010949d9e.png">

UnderSampling:

<img width="924" alt="Undersampling" src="https://user-images.githubusercontent.com/119356418/232606237-5fdaec1d-060e-481e-b8c2-903c689f3bad.png">

SMOTEEN:

<img width="930" alt="Over and Under Sampling" src="https://user-images.githubusercontent.com/119356418/232606270-08e05841-51b7-40b9-9629-139ef283bc22.png">

Balanced Random Forest Classifer:

<img width="680" alt="BalancedRandomForestClassifer" src="https://user-images.githubusercontent.com/119356418/232605891-2c74d80b-7904-45e1-9750-74e98c02ddbf.png">

Easy Ensemble Classifier:

<img width="666" alt="EasyEnsembleClassifier" src="https://user-images.githubusercontent.com/119356418/232605927-4e69fc1f-2211-43a6-965f-f793fcdf6c48.png">

SUMMARY

EasyEnsembleClassifier shows to be the most effective by providing a high score for all risk loans as a great value for overall analysis.  It provides a highest score for all risk loans.

