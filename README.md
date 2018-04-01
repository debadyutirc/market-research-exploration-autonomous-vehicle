# market-research-exploration-autonomous-vehicle
Repository for exploration and modelling on data collected by Himanshu on the perception of autonomous vehicles

## Dependencies
Python = 3.6
Scikit-Learn
Pandas
Numpy
Matplotlib
Seaborn

## Running the notebook
1. Git clone the repo or download zip
2. Navigate to the extracted directory
3. Start Jupyter Notebook

## Data details
This dataset was prepared by a friend in the form of a survey sento out to friends and aquaintances in social media as a part of the MSc dissertation project
The main objective of the survey was to find out the perceived acceptance of autonomous vehicles. The respondents were mainly from India and some from Europe.

## Whats in the notebook
The notebook explores an end to end data processing / mining / analytics / science ;-) pipeline. First the data is read and some aggregate ratios are generated, followed by some plots to understand the data. Subsequently feature engineering steps are performed to encode the categorical and rank variables to transform them into numeric data. Correlation of the independent variables with the label i.e driving experience is explored. Logistic Regression and Random forest models are initialized and trained followed by predictions and accuracy scoring and K-Fold crossvalidation.
