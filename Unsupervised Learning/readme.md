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
