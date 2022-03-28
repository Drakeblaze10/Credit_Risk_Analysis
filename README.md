# Credit_Risk_Analysis

## Overview of Analysis
The purpose of this analysis is to apply machine learning to credit card risk. Using, Oversampling, SMOTE, undersampling, ClusterCentroids, as well as Smoteen algorithm to calculate whether credit cards from lendingclub are at risk. Then I use balance random forest classifier and easy ensemble classifier to reduce bias and predit credit risk.

## Results
# Naive Random Oversampling
- Balanced Accuracy Score: 0.65
- Precision/recall Score:
![RandomOverSampling](https://github.com/Drakeblaze10/Credit_Risk_Analysis/blob/main/Resources/oversampling_cri.png)

# SMOTE Oversampling
- Balanced Accuracy Score: 0.62
- Precision/recall Score:
![SmoteSampling](https://github.com/Drakeblaze10/Credit_Risk_Analysis/blob/main/Resources/smote_cri.png)

# Cluster Centroids Undersampling
- Balanced Accuracy Score: 0.52
- Precision/recall Score:
![UnderSampling](https://github.com/Drakeblaze10/Credit_Risk_Analysis/blob/main/Resources/undersampling_cri.png)

# SMOTEEN Over- and Undersampling
- Balanced Accuracy Score: 0.64
- Precision/recall Score:
![SMOTEENSampling](https://github.com/Drakeblaze10/Credit_Risk_Analysis/blob/main/Resources/smoteen_cri.png)

# Balanced Random Forest Classifier
- Balanced Accuracy Score: 0.79
- Precision/recall Score:
![RandomForest](https://github.com/Drakeblaze10/Credit_Risk_Analysis/blob/main/Resources/randomforest_cri.png)

# Easy Ensemble Classifier
- Balanced Accuracy Score: 0.92
- Precision/recall Score:
![EasyEnsemble](https://github.com/Drakeblaze10/Credit_Risk_Analysis/blob/main/Resources/ensemble_cri.png)

## Summary
Out of the six machine learning models, undersampling seems to come the most short. With a balanced accuracy score of 0.52 and a recall of 0.44. In all of these models, the precision for low_risk is fairly high, being in the upper 90%. Meaning that the cards are most likely to fall into the low_risk category. So a model with a high recall, especially in high_risk and in combination with a higher balance accuracy score, would be the most beneficial. Easy Ensemble not ony has a high balanced accuracy score but a high recall and precision both within in the 90% predicting the higher likelyhood of discovering credit risks.