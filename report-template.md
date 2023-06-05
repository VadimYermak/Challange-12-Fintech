# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.-
    We are training the model to identify risky loans.
* Explain what financial information the data was on, and what you needed to predict.-
    We have information about the loans and their status.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).-
    We are trying to predict loan status.
* Describe the stages of the machine learning process you went through as part of this analysis.-
    1.Create 2 dataframe with features and label
    2.Value_conts and train_test_split
    3.Creating model with LogisticRegression
    4.Fit model
    5.Predicting
    6.Results(Balanced Accuracy Score, Confusion matrix, Classificatiion report)
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).-
    We have imbalanced data, 75036/2500, we made RandomOverSampler technique.
## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
   
          pre       rec       spe        f1       geo       iba       sup

  0       1.00      0.99      0.91      1.00      0.95      0.91     18765
  1       0.85      0.91      0.99      0.88      0.95      0.90       619

avg/      0.99      0.99      0.91      0.99      0.95      0.91     19384
total

Balanced Accuracy Score = 0.95

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
         pre       rec       spe        f1       geo       iba       sup

 0       1.00      0.99      0.99      1.00      0.99      0.99     18765
 1       0.84      0.99      0.99      0.91      0.99      0.99       619

avg/     0.99      0.99      0.99      0.99      0.99      0.99     19384
total

Balanced Accuracy Score = 0.99
## Summary

Balanced Accuracy Score better in second model with OverSampled data.


Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )-

I think that better to use 2 model because it has better Accuracy Score and Precision and Recall for risky loans.

