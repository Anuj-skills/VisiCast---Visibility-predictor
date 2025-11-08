
# Visibility distance prediction

## Problem Statement :-

The objective of this project is to develop a machine learning model that can accurately predict the maximum visibility distance in a given location and weather condition. The model should take into account various weather parameters such as humidity, temperature, wind speed, and atmospheric pressure, as well as geographical features such as elevation, terrain, and land cover. The model should be trained on a large dataset of historical weather and visibility data, and validated using a separate test dataset. The ultimate goal is to provide a tool that can help improve safety and efficiency in various applications such as aviation, transportation, and outdoor activities.


## Tech Stack Used

1. Python
2. Machine learning algorithms 
3. MongoDB

## Models Used

* [K-Means](https://www.javatpoint.com/k-means-clustering-algorithm-in-machine-learning)
* [LogisticRegression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)

From these above models after hyperparameter optimization we selected these two models which were K-Means for clustering and Logistic Regression for classification and used the following in Pipeline.

* GridSearchCV is used for Hyperparameter Optimization in the pipeline.

## `src` is the main package folder which contains

**Components** : Contains all components of Machine Learning Project

- Data Ingestion
- Data Validation
- Data Transformation
- Data Clustering
- Model Trainer
- Model Evaluation
- Model Pusher

**Custom Logger and Exceptions** are used in the Project for better debugging purposes.

## Conclusion

- This Project can be used in real-life by Users.

