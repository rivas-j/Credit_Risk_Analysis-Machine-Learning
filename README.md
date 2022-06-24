# Credit_Risk_Analysis

## Overview of the analysis: Explain the purpose of this analysis.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then, we used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, we compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. The purpose is to evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.
There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models 

- Random Oversampler
![Random Oversampler](https://github.com/rivas-j/Credit_Risk_Analysis/blob/386a96bcc459c26c60a18db4d51d6db21df909c7/Resources/1_Random_Oversampling.png)
- SMOTE Oversampler
![SMOTE Oversampler](https://github.com/rivas-j/Credit_Risk_Analysis/blob/386a96bcc459c26c60a18db4d51d6db21df909c7/Resources/2-SMOTE_Oversampling.png)
- ClusterCentroids Undersampler
![Undersampler](https://github.com/rivas-j/Credit_Risk_Analysis/blob/386a96bcc459c26c60a18db4d51d6db21df909c7/Resources/3-Undersampling.png)
- SMOTEENN Combination (Over and Under) Sampling
![SMOTEENN Combination](https://github.com/rivas-j/Credit_Risk_Analysis/blob/386a96bcc459c26c60a18db4d51d6db21df909c7/Resources/4-SMOTEEN_Over-Under-Sampling.png)
- Balanced Random Forest Classifier
![Balanced Random Forest](https://github.com/rivas-j/Credit_Risk_Analysis/blob/386a96bcc459c26c60a18db4d51d6db21df909c7/Resources/5-BalancedRandomForest.png)
- Easy Ensemble Classifier
![Easy Ensemble Classifier](https://github.com/rivas-j/Credit_Risk_Analysis/blob/386a96bcc459c26c60a18db4d51d6db21df909c7/Resources/6-EasyEnsembleClassifier.png)


## Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
