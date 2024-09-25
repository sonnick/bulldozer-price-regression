# bulldozer-price-regression

## Predicting the Sale Price of Bulldozers using Machine Learning
At the end of this project, we'll have a trained machine learning model which predicts the sale price of a bulldozer given different characteristics about it.

1. **Problem defition**
Given some past data of how much similar bulldozers have been sold for? and characteristics ,How well can we predict the future sale price of a bulldozer?

2. **Data**
The data is downloaded from the Kaggle Bluebook for Bulldozers competition: https://www.kaggle.com/c/bluebook-for-bulldozers/data Train.csv is the training set, which contains data through the end of 2011. Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 Test.csv is the test set, It contains data from May 1, 2012 - November 2012

3. **Evaluation**
Our evaluation metric would be the root mean squared log error (RMSLE). As with many regression evaluations, the goal will be to get this value as low as possible.

To see how well our model is doing, we'll calculate the RMSLE.

4. **Features**
Features defines the internal structure of a dataset. During this step, we will start finding out what you can about the data.

One of the most common ways to do this, is to create a data dictionary.

For this dataset, Kaggle provide a data dictionary which contains information about what each attribute of the dataset means.
