# Module 12 Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The purpose of the analysis is to use historical data of past lending activity to build a model that can identify the creditworthiness of borrowers and predict whether or not a loan will be high risk or not. The analysis will be used to evaluate the performance of these models and make a recommendation on whether they should be used to predict credit risk.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Balanced accuracy of 0.9520479254722232
  * Description of Model 1 precision    recall  f1-score   support

                    0       1.00      0.99      1.00     18765
                    1       0.85      0.91      0.88       619

              accuracy                           0.99     19384
              macro avg       0.92      0.95      0.94     19384
          weighted avg       0.99      0.99      0.99     19384



* Machine Learning Model 2:
  * Balanced accuracy of 0.9936781215845847
  * Description of Model 2 precision    recall  f1-score   support

                        0       1.00      0.99      1.00     18765
                        1       0.84      0.99      0.91       619

                  accuracy                           0.99     19384
                  macro avg       0.92      0.99      0.95     19384
              weighted avg       0.99      0.99      0.99     19384

## Summary
Model 2 is the best choice because it improves upon model 1 for f1 and recall while only slightly regressing on precision for high risk loans. Both models perform very well for healthy loans, while model 2 has a higher balanced accuracy. Using model 2 will help allow the bank to make the most informed decisions on loans.

