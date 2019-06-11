# MSDS 697 Final Project - Grocery Reorder Prediction

*Team Members: Evan Calkins, Brian Dorsey, Sankeerti Haniyur, Chris Olley, & Connor Swanson*

## Project Goals

- Work with a large dataset (>= 3GB)
- Preprocess data, train, and evaluate a machine learning model on AWS EMR using Apache Spark
- Analyze the impact of EMR cluster size on performance

## Modeling

- Generate target labels and user-specific features around grocery purchasing
- Hosted our data in a MongoDB cluster
- RandomForest model achieved an F1 score of 0.857

## Links

- Data: https://www.kaggle.com/c/instacart-market-basket-analysis
- Spark SQL preporcessing and target label creation: https://github.com/skhaniyur/instacart-reorder-prediction/blob/master/SparkSQL%20Data%20Manipulation%20v2.ipynb
- Additional feature engineering and ML model: https://github.com/skhaniyur/instacart-reorder-prediction/blob/master/Data%20Processing%20to%20Random%20Forest%20Final%20Script.ipynb
