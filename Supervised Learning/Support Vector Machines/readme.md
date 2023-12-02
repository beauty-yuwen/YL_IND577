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






