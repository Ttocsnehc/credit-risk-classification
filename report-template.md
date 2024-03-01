# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

  * Balanced Accuracy: 0.967989851522121
  * Precision for Class 0: 1.00, Class 1: 0.84
  * Recall for Class 0: 0.99, Class 1: 0.94


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

  * Balanced Accuracy: 0.9935981855334257
  * Precision for Class 0: 1.00, Class 1: 0.84
  * Recall for Class 0: 0.99, Class 1: 0.99
 


Machine Learning Process:
* Preprocessing the Data. Spliting Variables
* Training the Model using LogisticRegression
* Making Predictions
* Evaluating the Model. Finding the Balanced Accuracy, Precision, Recall, and F1-Score

* Resampling the Data using RandomOverSampler
* Training the Model using LogisticRegression
* Making Predictions
* Evaluating the Model. Finding the Balanced Accuracy, Precision, Recall, and F1-Score




## Summary

Model 2 gave us a better performance over model 1. It had a better balance score (0.9936 vs. 0.9680) and a better recall as well (0.99 vs 0.94). Both models showed the same precision. Model 2 seem to be more adept at predicting positive outcomes without increasing false positives too much. 

Yes, the choice of model depends on the specific problem you're solving. If predicting positive cases (1s) accurately is crucial, prioritize models with higher recall for Class 1. If avoiding false positives is more important, then focus on precision. 



