Ensemble methods
================
In this file, I will learn to use ensemble methods.
## What are ensemble methods?
Ensemble methods in machine learning involve constructing a set or "ensemble" of multiple models and combining their predictions to improve overall performance. These methods are particularly powerful when individual models have different strengths and weaknesses or when they are based on different algorithms. Ensemble methods aim to reduce overfitting, enhance generalization, and often result in more robust and accurate predictions compared to individual models. There are two main types of ensemble methods: 
### bagging
* Hard Voting:

Hard voting is a type of ensemble method in machine learning where multiple individual models (classifiers or regressors) make predictions on a new data point, and the final prediction is determined by a majority vote in the case of classification or an average in the case of regression. In hard voting, each model has an equal say, and the class or value with the most votes or the highest average is selected as the final prediction.
* Bagging:

Bagging methods involve training multiple instances of the same learning algorithm on different subsets of the training data. The idea is to introduce diversity among the models by using different subsets of the data. The predictions of individual models are then combined, typically through averaging (for regression) or voting (for classification).
* Random Forests:
  
An ensemble of decision trees, where each tree is trained on a random subset of the training data and a random subset of features at each split.
### boosting
* AdaBoost:

Sequentially trains a series of weak learners, giving more emphasis to misclassified instances. The final model combines the predictions of all weak learners.
* Gradient boosting:

Builds a series of decision trees sequentially, with each tree trying to correct the errors of the combined ensemble so far. Common implementations include XGBoost, LightGBM, and CatBoost.
### I try to do these ensemble methods with a dataset
The dataset I will be using in this file is the 'titanic' dataset. This dataset describes information about the passengers on the Titanic, including age, gender, etc. I will use this information to build a model to predict whether or not the passengers were spared.
* survival	Survival	0 = No, 1 = Yes
* pclass	Ticket class	1 = 1st, 2 = 2nd, 3 = 3rd
* sex	Sex	
* Age	Age in years	
* sibsp	# of siblings / spouses aboard the Titanic	
* parch	# of parents / children aboard the Titanic	
* ticket	Ticket number	
* fare	Passenger fare	
* cabin	Cabin number	
* embarked	Port of Embarkation	C = Cherbourg, Q = Queenstown, S = Southampton
