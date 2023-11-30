Decision and Regression Trees
=============================
In this file, I am going to explain and build decision and regression trees.
Regression trees are included in decision trees.

1.Decision Trees
--------------
### What are the decision trees?
Decision tree is a popular supervised machine learning algorithm for classification and regression tasks. It is a tree structure where each internal node represents a decision based on a particular feature, each branch represents the outcome of that decision, and each leaf node represents the final output or prediction.

Key components of a decision tree:
#### 1.Root Node:
The topmost node in the tree, representing the initial decision based on the most important feature. 
#### 2.Internal Nodes:
Nodes in the middle of the tree that represent decisions based on specific features. Internal nodes split the data into subsets based on feature conditions.
#### 3.Branches:
Branches or edges connect nodes and represent the possible outcomes of a decision based on the associated feature condition.
#### 4.Leaves:
Terminal nodes at the bottom of the tree that represent the final prediction or output.
#### 5.Decision Rules:
The conditions at each internal node, known as decision rules, are based on specific features of the input data. These rules determine how the data is split as it traverses the tree.
#### 6.Predictions:
Each leaf node corresponds to a specific class label (for classification) or a predicted numerical value (for regression).
### How decision trees work?
#### Training:
##### Feature Selection: 
The algorithm selects the feature that best splits the data based on a criterion (e.g., Gini impurity for classification, mean squared error for regression).
##### Splitting: 
The dataset is split into subsets based on the selected feature and its conditions.
##### Recursive Process: 
The splitting process is applied recursively to each subset until a stopping criterion is met.
##### Prediction:
During prediction, a new data point traverses the tree from the root to a leaf node based on the decision rules learned during training. The leaf node's associated class label or predicted value is then assigned to the input data.

2.Regression Trees
------------------
A regression tree is a type of decision tree used for regression tasks. Unlike classification trees, which are designed for predicting categorical outcomes, regression trees are used to predict a continuous target variable. The primary goal of a regression tree is to partition the input space into distinct regions and assign a constant value (the predicted value) to each region.

Similar to classification trees, a regression tree has nodes, branches, and leaves.

3.Data Description
------------------
In order to understand decision trees clearly, I choose a real dataset to build classification trees and regression trees respectively. 
