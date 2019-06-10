# MSDS 697 Final Project - Grocery Reorder Prediction

*Team Members: Evan Calkins, Brian Dorsey, Sankeerti Haniyur, Chris Olley, & Connor Swanson*

## Project Background

This was our final project for the Distributed Data Systems course at USF. This course was focused on the use of big data technologies in a distributed computing environment. The goal of the project was to work with a large dataset (minimum 3 gb) to preprocess data, train and evaluate a machine learning model on AWS EMR using Apache Spark. A secondary goal was to analyze the impact of EMR cluster size on performance.

## Dataset & Research Question

Our group chose to work with a dataset of customer grocery orders provided by online grocery delivery app, Instacart, with the aim of predicting which products a user is likely to purchase in their next order. To do this, we joined together data from six csvs to generate target labels and engineer user-specific features around grocery purchase habits. We hosted our data in a MongoDB in order to replicate the architecture required by a larger, more integral application. Our resulting RandomForest model achieved an F1 score of 0.857.

## Important Links

- Data source: https://www.kaggle.com/c/instacart-market-basket-analysis
- Spark SQL preporcessing and target label creation: https://github.com/ecalkins/msds697-grocery-reorder-prediction/blob/master/SparkSQL%20Data%20Manipulation%20v2.ipynb
- Additional feature engineering and ML model: https://github.com/ecalkins/msds697-grocery-reorder-prediction/blob/master/Data%20Processing%20to%20Random%20Forest%20Final%20Script.ipynb
