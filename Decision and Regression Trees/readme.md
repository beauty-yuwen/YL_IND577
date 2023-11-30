Decision Trees
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
The name of dataset is "loan_data". I will use lending data from 2007-2010 and be trying to classify and predict whether or not the borrower paid back their loan in full.
Here are what the columns represent:
* credit.policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
* purpose: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").
* int.rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.
* installment: The monthly installments owed by the borrower if the loan is funded.
* log.annual.inc: The natural log of the self-reported annual income of the borrower.
* dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income).
* fico: The FICO credit score of the borrower.
* days.with.cr.line: The number of days the borrower has had a credit line.
* revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).
* revol.util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).
* inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months.
* delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
* pub.rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).
