# Hierarchical Clustering Algorithm:

Also called Hierarchical cluster analysis or HCA is an unsupervised clustering algorithm which involves creating clusters that have predominant ordering from top to bottom.

For e.g: All files and folders on our hard disk are organized in a hierarchy.

The algorithm groups similar objects into groups called clusters. The endpoint is a set of clusters or groups, where each cluster is distinct from each other cluster, and the objects within each cluster are broadly similar to each other.

This clustering technique is divided into two types:

(1) Agglomerative Hierarchical Clustering

(2) Divisive Hierarchical Clustering

## (1)Agglomerative Hierarchical Clustering:

(a) Make each data point a single-point cluster → forms N clusters.

(b) Take the two closest data points and make them one cluster → forms N-1 clusters.

(c) Take the two closest clusters and make them one cluster → Forms N-2 clusters.

(d) Repeat step-3 until you are left with only one cluster.


There are several ways to measure the distance between clusters in order to decide the rules for clustering, and they are often called Linkage Methods. Some of the common linkage methods are:

Complete-linkage: the distance between two clusters is defined as the longest distance between two points in each cluster.

Single-linkage: the distance between two clusters is defined as the shortest distance between two points in each cluster. This linkage may be used to detect high values in your dataset which may be outliers as they will be merged at the end.

Average-linkage: the distance between two clusters is defined as the average distance between each point in one cluster to every point in the other cluster.

Centroid-linkage: finds the centroid of cluster 1 and centroid of cluster 2, and then calculates the distance between the two before merging.

The choice of linkage method entirely depends on you and there is no hard and fast method that will always give you good results. Different linkage methods lead to different clusters.

The point of doing all this is to demonstrate the way hierarchical clustering works, it maintains a memory of how we went through this process and that memory is stored in Dendrogram.

## What is a Dendrogram?

A Dendrogram is a type of tree diagram showing hierarchical relationships between different sets of data.

As already said a Dendrogram contains the memory of hierarchical clustering algorithm, so just by looking at the Dendrgram you can tell how the cluster is formed.

## Note:- 

(1) Distance between data points represents dissimilarities.

(2)Height of the blocks represents the distance between clusters.

## (2)Divisive Hierarchical Clustering:

In Divisive or DIANA(DIvisive ANAlysis Clustering) is a top-down clustering method where we assign all of the observations to a single cluster and then partition the cluster to two least similar clusters. Finally, we proceed recursively on each cluster until there is one cluster for each observation. So this clustering approach is exactly opposite to Agglomerative clustering.

There is evidence that divisive algorithms produce more accurate hierarchies than agglomerative algorithms in some circumstances but is conceptually more complex.

In both agglomerative and divisive hierarchical clustering, users need to specify the desired number of clusters as a termination condition(when to stop merging).

![hierarchy cluster type](https://user-images.githubusercontent.com/55452866/88622109-ac85c400-d0bf-11ea-803f-b90c718c8adb.jpeg)

# Steps in the Notebook:

(1)Importing the library.

(2)Importing the dataset.

(3)Using the dendrogram to find otimal number of clusters.

![image](https://user-images.githubusercontent.com/55452866/88622343-3f266300-d0c0-11ea-8a7c-8f3a3cf8a78f.png)


(4)Training the model.

(5)Visualising the Cluster.

![image](https://user-images.githubusercontent.com/55452866/88622406-654c0300-d0c0-11ea-85de-b3e06bd76d45.png)

