# House-Price-Prediction (ML Project)
**Scikit-learn Design:**

Primarily, three types of objects
1.Estimators - It estimates some parameter based on a dataset. Eg. imputer. It has a fit method and transform method. Fit method - Fits the dataset and calculates internal parameters

2.Transformers - transform method takes input and returns output based on the learnings from fit(). It also has a convenience function called fit_transform() which fits and then transforms.

3.Predictors - LinearRegression model is an example of predictor. fit() and predict() are two common functions. It also gives score() function which will evaluate the predictions.

**Feature Scaling:**

Primarily, two types of feature scaling methods:
1. Min-max scaling (Normalization)

    (value - min)/(max - min).

    Sklearn provides a class called MinMaxScaler for this
    
2. Standardization

    (value - mean)/std.

    Sklearn provides a class called StandardScaler for this

