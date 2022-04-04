# bulldozer_price_prediction_project
In this project we are going to be going through an example of machine Learning the project
with the plan of predicting sale price of bulldozer.

## 1. Problem Definition 
How well can i predict the furture sale price of a bulldozer given it charateristics and previous examples on how much similar bulldozer have been sold before.

## 2. Data
The data is downloaded from the kaggle Bluebook for bulldozer competition:  https://www.kaggle.com/competitions/bluebook-for-bulldozers/data

This data is split into three parts:

* Train.csv is the training set, which contains data through the end of 2011.

* Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.

* Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.

## 3. Evaluation
* The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.
For more on Evaluation for this project Check: https://www.kaggle.com/competitions/bluebook-for-bulldozers/overview/evaluation
 
**Note:** The goal for most regrassion metric is to minimize the error. For Example, our goal for this project will be to build a machine learning model which Minimum RMSLE.

## 4. Features
Kaggles provides a data dictionary datailing all of the features of the dataset. You can view this data dictionary on google-sheet: https://www.kaggle.com/competitions/bluebook-for-bulldozers/data?select=Data+Dictionary.xlsx
