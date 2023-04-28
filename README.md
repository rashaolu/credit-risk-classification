# Credit-risk-classification Challenge

## Overview of the Analysis

The purpose of this challenge is to use various techniques to train and evaluate a model based on loan risk. the dataset used is of historical lending activity from a peer to peer lending services company to buils a model that can identfy the creditworthiness of borrowers.

This challenge splits the data into training and testing sets, creates a Logistical regression model using the orginal data. Using RandomSampler module, a new sample dataset is created from the orgional dataset. then a logistical regression moel is predicted with the resampled training data.

## Results

* Machine Learning Model 1(origional data)
    * Accuracy: 0.99 (99%)
    * Precision: 0.87 (87%)
    * Recall: 0.89 (89%)
  
* Machine Learning Model 2 (resampled data)
    * Accuracy: 1.00 (100%)
    * Precision: 0.87 (87%)
    * Recall: 1.00 (100%)
    
## Summary

The original dataset model had an accuracy of 99% precision of 87% and recall of 89%. These are adequate findings and the model would be reliable to use. the resampled dataset had 100% accuracy, 87% percision and 100% recall. This model yeilded better results than the origional data model with high recall and accuracy. Something to note is that the precision for both of the models are the same. I would reccomend using the resampled model over the orgianl model, however both models can be utalized to determine the creditworthiness of borrowes. 
The performance depnds on both the 1's and the 0's. It is important to see how the model works at predicting false positives, and false negatives. Both of the factors are important and one doesn't outweigh the other and they should both be looked at.