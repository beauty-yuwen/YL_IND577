Neural Nets
===========
In this file, I will introduce Neural Nets in machine learning.

What is Neural Nets?
------------------
Neural networks, are computational models inspired by the structure and functioning of the human brain. They are a subset of machine learning algorithms that are particularly well-suited for tasks such as pattern recognition, classification, regression, and decision making.

The basic building block of a neural network is the artificial neuron, also known as a perceptron. Neurons are organized into layers, and these layers form the structure of the neural network. There are typically three types of layers:

### Input Layer:
This layer receives input features or data and passes them to the next layer.
### Hidden Layers:
These layers lie between the input and output layers.
Neurons in hidden layers apply weighted transformations to the inputs and pass the results to the next layer.
### Output Layer:
This layer produces the final output of the neural network.
The number of neurons in the output layer depends on the nature of the task (e.g., binary classification, multiclass classification, regression).

![image](https://github.com/beauty-yuwen/YL_IND577/blob/main/screenshots/Neural_network_example.svg)

How to implement Neural Nets?
------------------
Neural networks use a process called training or learning to adjust the weights associated with each connection between neurons. During training, the network learns to map input data to the correct output by iteratively adjusting these weights based on the error or difference between predicted and actual outputs.

Data used to implement Neural Nets
---------------------------------
In order to implement neural nets, I choose a real dataset to do this. The name of dataset is "loan_data". I will use lending data from 2007-2010 and be trying to classify and predict whether or not the borrower paid back their loan in full. Here are what the columns represent:

credit.policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
purpose: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").
int.rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.
installment: The monthly installments owed by the borrower if the loan is funded.
log.annual.inc: The natural log of the self-reported annual income of the borrower.
dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income).
fico: The FICO credit score of the borrower.
days.with.cr.line: The number of days the borrower has had a credit line.
revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).
revol.util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).
inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months.
delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
pub.rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).
