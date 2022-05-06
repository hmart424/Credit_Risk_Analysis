# Credit Risk Analysis

## Overview of the Analysis

In todays Analysis we predicted credit risk. Credit risk is an inherently unbalanced classification problem. Therefor we will employ different techniques to train and evaluate models with unbalanced classes such as imbalanced-learn and scikit-learn. WE oversampled the data using RandomOverSampler and SMOTE algorithms. Ill compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier as well!

* Naive Random Oversampling: The balanced accuracy score is at 67%. The percesion for high_risk os at 1% and the recall is 74%
![Screen Shot 2022-05-05 at 11 55 22 PM](https://user-images.githubusercontent.com/95835840/167069615-6284d2d3-5d0d-4e7a-a9b4-0e7af60c87c5.png)

* SMOTE oversampling : accuracy score is 66.2%, the precision for the high_risk loans is at 1% and recall is 69%.
![Screen Shot 2022-05-06 at 12 00 45 AM](https://user-images.githubusercontent.com/95835840/167070060-cec1bde0-3e22-45dd-9fb8-3221e7f93679.png)

* Undersampling results: balanced accuracy score is 54% overall, the precision is at 99% and the recall is 42%
![Screen Shot 2022-05-06 at 12 04 36 AM](https://user-images.githubusercontent.com/95835840/167070332-784c90ba-46c3-4e82-b5e7-0649b0453288.png)

* Combination : balanced accuracy score is 54.7% the precision is 99% and the recall is 57% overall
![Screen Shot 2022-05-06 at 12 06 10 AM](https://user-images.githubusercontent.com/95835840/167070537-8634744c-cb73-4db6-a082-fb5b73bfa1a9.png)

* Balanced Random Forest Classifier: the accuracy is 78% the precision is 99% and the recall is 88%
![Screen Shot 2022-05-06 at 12 08 38 AM](https://user-images.githubusercontent.com/95835840/167070664-eb864500-b433-4741-8621-8b6f4007fe6e.png)

* Easy Ensemble AdaBoost Classifier: the accuracy score is 91.7% the precision is 99% and the recall is 94%
![Screen Shot 2022-05-06 at 12 11 34 AM](https://user-images.githubusercontent.com/95835840/167070925-64e8120d-03e0-487d-b9a2-253c9b3f7e01.png)

## Summary

In conclusion, credit-risk is a difficult thing to predict. The precision scores for prediciting high risk was low for all six models. The Balanced Random Forest Classifier and the Easy Ensemble Classifier gave the highest recall scores of 0.92 and 0.94 for high and low risk. I would recommend to use the Easy Ensemble Classsifer because it had the highest balanced accuracy score of 0.93, the company should be aware of the implications of the precision scores.
