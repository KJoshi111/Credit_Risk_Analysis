# Credit_Risk_Analysis
Module 17 Challenge
This new assignment consists of three technical analysis deliverables and a written report. The list is following:

## Deliverable 1: Use Resampling Models to Predict Credit Risk
Using our knowledge of the imbalanced-learn and scikit-learn libraries, we evaluated three machine learning models by using resampling to determine which is better at predicting credit risk. First, we used the oversampling RandomOverSampler and SMOTE algorithms, and then we used the undersampling ClusterCentroids algorithm. Using these algorithms, resampled the dataset, viewed the count of the target classes, trained a logistic regression classifier, calculated the balanced accuracy score, generated a confusion matrix, and generated a classification report.


## Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
Using our knowledge of the imbalanced-learn and scikit-learn libraries, we used a combinatorial approach of over- and undersampling with the SMOTEENN algorithm to determine if the results from the combinatorial approach are better at predicting credit risk than the resampling algorithms from Deliverable 1. Using the SMOTEENN algorithm, we resampled the dataset, viewed the count of the target classes, trained a logistic regression classifier, calculated the balanced accuracy score, generated a confusion matrix, and generated a classification report.


## Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
Using our knowledge of the imblearn.ensemble library, we trained and compared two different ensemble classifiers, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk and evaluate each model. Using both algorithms, we resampled the dataset, viewed the count of the target classes, trained the ensemble classifier, calculated the balanced accuracy score, generated a confusion matrix, and generated a classification report.


## Deliverable 4: A Written Report on the Credit Risk Analysis.
### Results:
#### Naive Random Oversampling:

![image](https://github.com/KJoshi111/Credit_Risk_Analysis/blob/main/Images/NaiveROS.png)

1. Balanced Accuracy: 0.6366972052004142
2. Precision : The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall:  High/low Risk =  0.62/0.65 

#### SMOTE Oversampling:

![Image](https://github.com/KJoshi111/Credit_Risk_Analysis/blob/main/Images/SMOTE.png)

1. Balanced Accuracy: 0.6453944426314708
2. Precision : The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall:  High/low Risk =  0.63/0.66

#### Undersampling:

![Image](https://github.com/KJoshi111/Credit_Risk_Analysis/blob/main/Images/Undersampling.png)

1. Balanced Accuracy: 0.6453944426314708
2. Precision : The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall:  High/low Risk =  0.61/0.45

#### Combination Under-over Sampling:

![image](https://github.com/KJoshi111/Credit_Risk_Analysis/blob/main/Images/comination.png)

1. Balanced Accuracy: 0.5293026900499977
2. Precision : The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall:  High/low Risk =  0.70/0.57

#### Balanced Random Forest Classifier:

![image](https://github.com/KJoshi111/Credit_Risk_Analysis/blob/main/Images/balanced%20random.png)

1. Balanced Accuracy: 0.7877672625306695
2. Precision : The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall:  High/low Risk =  0.67/0.91

#### Easy Ensemble AdaBoost Classfier:

![image](https://github.com/KJoshi111/Credit_Risk_Analysis/blob/main/Images/Easy%20Ensemble.png)

1. Balanced Accuracy: 0.925427358175101
2. Precision : The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall:  High/low Risk =  0.91/0.94

### Summary:
When working with balanced accuracy, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model. For the credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to choose with its .93 balanced accuracy. The other models were below .80 balanced accuracy. The precision for all models were similar and within an appropriate range. The recall score also needs to fall within 0 and 1, with numbers closer to 1 being the better model. The Easy Ensemble AdaBoost Classifier had the highest recall score, making it the final best machine learning model to choose for further credit card analysis.
With the help of all these tools we can make the money lending process a bit easy for the employees and easy-going for customres with minimising the risk factor for our financial institute.



