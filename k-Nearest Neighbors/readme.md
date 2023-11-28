K-Nearest Neighbors
===================
In this file, I will explain the K-Nearest Neighbors. It is also one of Supervised Learning Methods in machine learning.

What is K-Nearest Neighbors?
--------------------------
K-Nearest Neighbors, (often abbreviated as KNN) is a simple and widely used machine learning algorithm for performing classification and regression tasks. It is primarily used for non-parametric supervised learning. This algorithm makes predictions by finding the majority class or average objective value of the K nearest data points in the feature space. 

In k-NN classification, the output is a category feature. An object's classification is determined by a majority vote of its neighbors, and the object is assigned to the most common category among its k nearest neighbors (k is a positive integer, usually small).

In k-NN regression, the output is a specific value for the object. The value is the average of the k nearest neighbor values.

There are several main steps to perform this algorithm:

### KNN for classification
##### 1. Traininng
Include the data for training.
##### 2. Predicting
Given a new input sample, the algorithm identifies the K closest training instances to it in the feature space. This "is usually determined using a distance metric such as Euclidean distance.

When classifying, the algorithm assigns the most common category labels among the K nearest neighbors using a voting method.
### KNN for regression
##### 1. Training
Include the data for training.
##### 2. Predicting
Given a new input sample, the algorithm finds the K closest training samples to it.

In regression, the algorithm predicts the target value of the new sample by averaging the target values of the K nearest neighbor samples.
