# Predicting Bank Marketing Outcome
This is a documenation about deep learning project to predict if a customer would subsribe a term deposit of a bank or not, with Tensorflow.

## 1. Project Overview
* Project Objective
   * Prediction based on the classification with logistic regression
   * Target Feature
      * y: has the client subscribed a term deposit? 
      * value: binary(yes or no)

* About the Dataset
    * Dataset from UCI Machinie Learning Repository.
        * https://archive.ics.uci.edu/ml/datasets/bank+marketing
    * Customer data from May 2008 to November 2010.
    * 41188 rows with 20 columns.

* About the features
    * Please refer to the attribute information [here](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
    
## 2. Data Pre-processing

 * The target feature was encoded 1 and 0.
 * Categorical varibles were all transformed into dummy variables.
 * Insignificant features detected were removed as per the model summary result on logidtic regression by R. 
 * Insignificant featuers again removed as per the result of correlation plot by R. 
 * All numerical features standardized by Standard Scaler by 'sklearn'.
    
## 3. Modeling

![image](https://user-images.githubusercontent.com/46237445/50608069-b1e45200-0f0e-11e9-8294-d8716e43876f.png)

  * 9 input variables
  * K input between hidden layers
  * 1 output variable
  * Xavier Initializer
  * Leaky ReLU/ReLU & Sigmoid
  * AdamOptimizer
  * Cost function for logistic regression

## 4. Model Optimization

## 5. Conclusion