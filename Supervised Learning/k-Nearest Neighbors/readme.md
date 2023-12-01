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

Perform K-Nearest Neighbors in a real dataset
--------------------------
In order to perform  K-Nearest Neighbors, I found a real dataset to do both classification and regression.
### Data Description
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
