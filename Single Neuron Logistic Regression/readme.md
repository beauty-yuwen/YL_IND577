Single Neuron Logistic Regression
=================================
In this file, I will talk about Single Neuron Logistic Regression. First, the concept of Single Neuron Logistic Regression will be introduced. Then, I will use a real dataset to build a Single Neuron Logistic Regression model.

## What is Single Neuron Logistic Regression?
Single neuron logistic regression is a method of machine learning that uses a single neuron to implement logistic regression in a neural network. When implementing logistic regression in a neural network, multiple layers of neurons are usually involved, forming so-called logistic regression units or logistic neurons. However, in the case of a single neuron, the term is more broadly used to describe a simplified logistic regression model. It is similar to single neuron linear regression, except that here the predictor variables are dichotomous.

The key points of single neuron logistic regression are as follows:
#### 1. Input
#### 2. Sigmoid (Logistic) Activation Function:
Instead of the linear activation function used in linear regression, logistic regression uses a sigmoid (logistic) activation function. The linear activation function gives specific predicted values, while the sigmoid function maps any real value to a value between 0 and 1, representing a probability.
#### 3. Model Formulation:
P(Y=1∣X)=σ(W⋅X+b)

P(Y=1∣X) is the probability of the positive class given the input；

w are weights;

b is the bias term.
#### 4.Decision Boundary:
Similar to logistic regression, the decision boundary is determined by where the predicted probability equals 0.5.(<0.5 is 0; >0.5 is 1)
#### 5. Training:
During training, the model parameters (weights and bias) are updated iteratively using optimization algorithms to maximize the likelihood of the observed data.
#### 6. Cost Function:
By the 5th step, we will get the model with the least cost.
## Data Description
After knowing the steps to do the Single Neuron Logistic Regression, I choose a real dataset to repeate the procedure.

The name of the dataset is "nba_logreg". In this dataset, it displays 21 columns, 1,340 rows in table, which means it has 21 varibales and 1340 data points. It is a dataset for practicing classification. My goal is to predict if player will last 5 years in league.

Here is a description for the dataset:
![image](https://github.com/beauty-yuwen/YL_IND577/blob/main/screenshots/Screen%20Shot%202017-01-25%20at%2010.20.38%20AM.png)

The "TARGET_5Yrs" is the label in my logistic model. Other variables are features to help predict the label.
