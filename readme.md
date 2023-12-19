# Australian Vehicle Price Prediction

## Overview
This project involves the creation of a machine learning model for predicting vehicle prices based on a dataset. The primary objective is to train a model capable of accurately forecasting the price of a vehicle given certain features.

## Dataset
The dataset used for this project is the [Australian Vehicle Prices Dataset](https://www.kaggle.com/datasets/nelgiriyewithana/australian-vehicle-prices/).

## Analysis Steps

### 1. Data Exploration
- Examined the number of samples and features in the dataset.
- Identified the target column as 'Price'.
- Explored the data types of each column, distinguishing between numeric and categorical features.

### 2. Data Cleaning
- Checked and addressed missing values in the dataset.
- Removed duplicate entries.
- Discarded missing values, resulting in a reduction of approximately 14.82% of the original data.

### 3. Data Encoding
- Utilized one-hot encoding to convert categorical features into a numeric format.
- Replaced boolean values with 0 and 1.

### 4. Train-Test Split
- Segmented the dataset into input and output components.
- Applied a 70-30 train-test split for model evaluation.

### 5. Model Training and Evaluation
- Employed a polynomial regression model with degree 1, accompanied by feature scaling.
- Trained the model on the training set and evaluated its performance on both the training and test sets.
- Calculated and displayed the \(R^2\) values for assessing model accuracy.

### 6. Model Assessment
- Checked for potential overfitting by examining the difference between \(R^2\) values for the training and test sets.
- Assessed whether the model underfits the training set based on a specified threshold of 0.6.

## Results
- Achieved an \(R^2\) value of approximately 0.548 for the training set and 0.544 for the test set.
- The model did not exhibit significant overfitting, as the difference in \(R^2\) values was relatively small.
- The model did not underfit the training set, as the \(R^2\) value exceeded the specified threshold.

---

This summary provides an overview of the key steps undertaken in the code, the dataset used, and the results obtained from the machine learning model.