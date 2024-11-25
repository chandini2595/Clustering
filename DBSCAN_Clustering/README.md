# DBSCAN Clustering

DBSCAN (Density-Based Spatial Clustering of Applications with Noise) is a clustering algorithm that groups data points based on the density of points in their neighborhood. Unlike K-Means or Gaussian Mixture Models, it doesn't require the number of clusters to be specified in advance and can identify clusters of arbitrary shape, making it robust to noise and outliers.

**How DBSCAN Works:**

DBSCAN groups data points by identifying areas of high density and separating them from areas of low density. Here's how it works:

1. The algorithm starts by examining one data point and looking at the points in its neighborhood.
2. If the point is in a dense region, it becomes part of a cluster. The algorithm then expands the cluster by including all nearby points that are also in dense regions.
3. This process continues, growing the cluster by adding points that meet the density requirement.
4. If a point doesn't belong to any dense region, it is marked as noise or outlier.
5. The algorithm moves on to the next unvisited point and repeats the process until all points are either part of a cluster or marked as noise.

Colab link: https://colab.research.google.com/drive/1Q2Id52VIusLN_OZI6wg4uT45c3_I13Vm?usp=sharing

Youtube link: 
