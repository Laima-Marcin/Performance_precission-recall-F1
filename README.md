# Performance_precission-recall-F1
Translating model performance into Clinical Utility Solution

In this exercise, we are given a dataframe with ground truth labels as well as probabilities output by an algorithm that was developed to classify images as having a malignant tumor or not. 

Our job is to generate a Precision-Recall curve as well as an optional ROC AUC curve with the data in this dataframe.

Once we create these curves, we need to choose two different thresholds: 
* one that favors precision and 
* one that favors recall. 

We use these thresholds to calculate two separate F1 scores. 
Then, we also calculate the accuracy of our algorithm using these two different thresholds and we see that accuracy really isn't a great performance statistic when evaluating and interpreting the utility of our models.
