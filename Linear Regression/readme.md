The Single Neuron Linear Regression Model
========================================
In this file, the Single Neuron Linear Regression Model will be introduced.

Regression and Linear Regression
--------------------------------
Regression analysis is a set of statistical processes used to estimate the relationship between a "response" variable, ("label" in machine learning) and one or more independent variables ("features"). One of the most common uses of regression analysis is prediction. The rules between "labels" and "features" are obtained by supervised learning on a training set of data. Afterwards, a "feature" can be entered and its "label" can be predicted.

The most common form of regression analysis is linear regression, in which the rule between "label" and "feature" is used to find the straight line that best matches the rule.
![image](https://github.com/beauty-yuwen/YL_IND577/blob/main/screenshots/Linear_regression.svg)

This plot shows a simple linear regression between response variable y and an independent variable x.

However, linear regression outputs are continuous values and are therefore suitable for regression problems. Unlike regression problems, the final output of the model in classification problems is discrete values.
### So, how to do linear regression in python?
To do the analysis, I will use cancer statistics aggregated at the county level.
There are I will use the data in this dataset to build a linear regression model to predict 'target_deathrate'.
###### Dataset Description
There are a total of 33 variables in this dataset, namely 'avganncount'	'avgdeathsperyear'	'target_deathrate'	'incidencerate'	'medincome'	'popest2015'	'povertypercent'	'studypercap'	'binnedinc'	'medianage'	'medianagemale'	'medianagefemale'	'geography'	'percentmarried'	'pctnohs18_24'	'pcths18_24'	'pctsomecol18_24'	'pctbachdeg18_24'	'pcths25_over'	'pctbachdeg25_over'	'pctemployed16_over'	'pctunemployed16_over'	'pctprivatecoverage'	'pctprivatecoveragealone'	'pctempprivcoverage'	'pctpubliccoverage'	'pctpubliccoveragealone'	'pctwhite'	'pctblack'	'pctasian'	'pctotherrace'	'pctmarriedhouseholds'	'birthrate'. Besides, there are total 3,047 rows in this dataset.

Just because there are so many variables in this dataset, I will not show the data here, but I will give a data description in my python file.

The Single Neuron Linear Regression Model
----------------------------------------
Single neuron linear regression models are a more complex class of models than linear regression. It is a basic form of linear regression using single neurons in a neural network. To get such a model one needs to combine linear regression, single neuron model and use gradient descent method to get the optimal model. This model possesses minimum prediction error.
#### y=w1*x1+w2*x2+…+wn*xn+b

b here is the bias, w1...wn are weights for every features, y is prediction. I will also use the same dataset to build a Single Neuron Linear Regression Model and evaluate this model.
