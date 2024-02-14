## Overview:

This script performs data preprocessing and builds a ML pipeline to predict if income is over 50k or not, from the Adult Income dataset.


The code begins by loading the dataset and performing basic data preprocessing tasks such as handling missing values and encoding categorical variables
and then modifies the dataset by engineering new features and transforming existing ones.
A portion of the dataset is sampled to balance the classes.

A machine learning pipeline is created using imbalanced-learn's IMBPipeline and it consists of data transformation steps, sampling methods,
dimensionality reduction techniques, and classification algorithms.
Hyperparameter tuning is performed using randomized search cross-validation.
