# Iris Dataset Analysis

This repository contains data analysis and preprocessing of the famous Iris dataset using Python.

The project demonstrates:
- Data loading using Pandas
- Data exploration
- Checking null values and duplicates
- Converting categorical data into numeric
- Feature scaling (Normalization and Standardization)
  Tools Used:
- Python
- Pandas
- NumPy
- Scikit-learn
# Feature Scaling:
* Feature scaling is a data pre processing step, that improves (significantly) the performance of some 
machine learning algorithms.
* It makes sure that the features involved in the computation are on the similar scale. 
- This implies that the features involved should take similar ranges of values. 
* It prevents any one feature having high range values, to dominate the results.
* Machine learning algorithms, where feature scaling is advantageous include:
* linear regression, logistic regression, neural network, etc. that use gradient descent optimization,
* Distance algorithms like K nearest neighbors (KNN), K-means clustering, and support vector machine 
(SVM). 
* Tree-based algorithms like decision trees, random forest, xgboost, etc., on the other hand, are fairly 
insensitive to the scale of the features.
* Note that scaling the target values is generally not required.
* Two common techniques are Normalization and Standardization.# Data-Analysis-Iris-Dataset
* Normalization
* Also known as min-max scaling or min-max normalization.
* Scales down the values of the features between 0 and 1. 
* The general formula for normalization is given as:
𝑥𝑛𝑜𝑟𝑚 =𝑥−𝑥𝑚𝑖𝑛 / 𝑥𝑚𝑎𝑥−𝑥𝑚𝑖𝑛 and 𝑥𝑚𝑖𝑛 are the maximum and the minimum values of the feature respectively.
* When the value of 𝑥 is the minimum value in the column, the numerator will be 0, and hence 𝑥𝑛𝑜𝑟𝑚 is 
0.
* On the other hand, when the value of 𝑥 is the maximum value in the column, the numerator is equal to 
the denominator and thus the value of 𝑥𝑛𝑜𝑟𝑚 is 1.
* If the value of 𝑥 is between the minimum and the maximum value, then the value of 𝑥𝑛𝑜𝑟𝑚 is between 
0 and 1.
* Standardization
* Also called z-score normalization.
* Feature standardization makes the values of each feature in the data have zero mean and unit variance.
* Transforms the feature into standard normal distribution.
* The general method of calculation is to determine the distribution mean 𝜇 and standard deviation 𝜎 for 
each feature and calculate the new data point by the following formula:
𝑥𝑠𝑡𝑎𝑛𝑑 = 𝑥−𝜇/𝜎  where, 𝜇 = mean and  σ = Standard Deviation.
* Here the values are not restricted to a particular range
  
