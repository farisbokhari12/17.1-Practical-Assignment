17.1 Pracitical Assignment Report
---------------------

#### Introduction
This analysis compares several classifiers on a dataset regarding a Portuguese Banking Institution. It utilizes Logistic Regression, K-Nearest-Neighbors, Support Vector Machine, and Decision Tree to determine effective accuracy. This report will highligh some of the findings.

### Model (No Hyperparameters)
Below are the results for each models accuracy:

Dummy Classifier (Baseline)
Accuracy: 0.8865015780529255

Model  Train Time  Train Accuracy  Test Accuracy
0     Logistic Regression    2.682287        0.911806       0.911386
1     K-Nearest Neighbors    0.166826        0.927709       0.900704
2           Decision Tree    0.443978        1.000000       0.890022
3  Support Vector Machine  214.132053        0.922671       0.911750

From the above, we see that the highest test accuracy was the Support Vector Machine witha 0.911750 test accuracy as well as the logistic regression model marginally being lower at 0.911386 test accuracy. Comparing the training time both the Support Vector Machine had the longest training time in comparison to the rest with Logistic Regression being significantly faster to train at 214.132053 seconds and 2.682287. Overall based on purely training the models with no hyperparameter tuning the Logistic Regression model makes the most sense to utilize as the accuracy is only a little lower but the training time required is much faster.

### Model (Hyperparameters)


