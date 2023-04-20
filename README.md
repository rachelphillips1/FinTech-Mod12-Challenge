# FinTech-Mod12-Challenge

## Overview of the Analysis

The purpose of this analysis is to fit a model that can predict based on certain user features whether a person represents a good credit risk and should be eligible for a line of credit. The training features we usesd included the size of the requested loan, the interest rate of the loan, the amount of income made by the person, thir debt to income ratio, the number of open credit accounts they have, any derogatory marks on their credit, and their total debt.

First, we split the data into training and testing sets. Using the training data, we fit a model to predict whether the loan status would be healthy (0) or unhealthy (1). Then, we used our model on the testing data in order to determine the model's accuracy.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
 Model 1 was 95% accurate. The precision score was betewen 95 and 91%.


* Machine Learning Model 2:
Model 2 was 99% accurate making it the more accurate model. According to the classification report, this model was altogether more accurate than the first model.

## Summary
The second model performed better. From the lending perspective, it is safer to misclassify a healthy loan as unhealthy, as there is no risk to the lender in this case. However, it is more dangerous to misclassify an unhealthy loan as healthy as in that caswe the lender would have risked money on a potentially inadvisable investment.
