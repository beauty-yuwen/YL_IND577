Unsupervised Learning
====================
In machine learning, it is used to deal with unlabeled data. The techniques are really different from Supervised Learning.

Main techniques:
---------------
### 1. Clustering(partitioning problem)
* K-Means
* DBSCAN
* HDBSCAN
* Community Detection Algorithm in Graphs
### 2. Dimensionality Reduction
* PCA(principle Componant Analysis)
* Manifold Analysis

## Then, we will pay attention to K-Means and PCA.
### K-Means Clustering
#### What is K-Means Clustering?
K-means clustering is a popular unsupervised machine learning algorithm used for partitioning a dataset into K distinct, non-overlapping subsets (or clusters). The goal of K-means clustering is to group similar data points together and discover underlying patterns in the data.
#### How to do K-Means Clustering?
1. Pick K>=2;
2. Randomly sample K centroids from D;
3. Assign each x in D to the nearest centroids. Let Ci be the set of all x assigned to centroid i;
4. Update the centroids using the average of distance between every groups;
5. Repeat 3 and 4 until the centroids do not change.

## The Data

We will use a data frame with 777 observations on the following 18 variables.
* Private A factor with levels No and Yes indicating private or public university
* Apps Number of applications received
* Accept Number of applications accepted
* Enroll Number of new students enrolled
* Top10perc Pct. new students from top 10% of H.S. class
* Top25perc Pct. new students from top 25% of H.S. class
* F.Undergrad Number of fulltime undergraduates
* P.Undergrad Number of parttime undergraduates
* Outstate Out-of-state tuition
* Room.Board Room and board costs
* Books Estimated book costs
* Personal Estimated personal spending
* PhD Pct. of faculty with Ph.D.’s
* Terminal Pct. of faculty with terminal degree
* S.F.Ratio Student/faculty ratio
* perc.alumni Pct. alumni who donate
* Expend Instructional expenditure per student
* Grad.Rate Graduation rate

In this exercise, we will attempt to use KMeans Clustering to cluster Universities into to two groups, Private and Public.
