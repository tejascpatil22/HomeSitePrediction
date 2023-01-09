# HomeSitePrediction

## Why is this relevant?
Homesite, a leading provider of homeowner’s insurance, wants to know which of their customers will purchase an insurance given a certain quote about the price, to be able to 
refine their quotes such that they can sell more insurance. The same principle can be used to solve other product pricing problems.
The data provides a rich representation of customer as well as the policy information. 

## About this implementation
I'm using stacked models to come up with a good prediction.
It uses a meta-learning algorithm to learn how to best combine the predictions from two or more base machine learning algorithms.

The benefit of stacking is that it can harness the capabilities of a range of well-performing models on a classification or regression task and make predictions that have better performance than any single model in the ensemble. The predictions and the prediction errors of the base model inform the level 1 or higher level models to improve
upon the prediction of what the base models provide.
