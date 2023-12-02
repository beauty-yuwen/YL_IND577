Support Vector Machines
======================
In this file, I will introduce Support Vector Machines.

What is Support Vector Machines alogrithm?
-----------------------------------------
Support Vector Machines (SVM) is a supervised machine learning algorithm that is used for classification and regression tasks. It's a versatile algorithm that works well for both linear and non-linear data. SVM is particularly popular in classification problems and is known for its ability to handle high-dimensional spaces effectively.

The primary objective of SVM is to find the hyperplane that best separates the data points of different classes in feature space. The hyperplane is chosen in such a way that it maximizes the margin between the classes. The margin is defined as the distance between the hyperplane and the nearest data point from each class. The idea is to choose the hyperplane that maximizes this margin, as it is expected to generalize well to unseen data.

Key concepts and components of SVM include:

* Hyperplane: In a two-dimensional space, a hyperplane is a line. In higher-dimensional spaces, it becomes a hyperplane. For a binary classification problem, the hyperplane separates data points of one class from another.

* Margin: The margin is the distance between the hyperplane and the nearest data point from each class. SVM aims to maximize this margin.

* Support Vectors: Support vectors are the data points that are closest to the hyperplane and play a crucial role in defining the decision boundary.

* Kernel Trick: SVM can be extended to handle non-linear decision boundaries by using the kernel trick. Kernels allow the algorithm to implicitly map the input features into higher-dimensional spaces, making it possible to find a linear hyperplane in that space.

SVMs have different variants, such as linear SVM for linearly separable data and non-linear SVM using kernels for more complex relationships. They are widely used in various applications, including image classification, text classification, and bioinformatics, among others.

Data used to implement Support Vector Machines
---------------------------------------------
I also use the 'loan_data' to finish the classification work. The response variable is 'fully paid or not'.
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





