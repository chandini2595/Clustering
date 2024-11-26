#  Hierarchial Clustering 

Hierarchical clustering is a method of clustering that builds a hierarchy of clusters. It is often visualized using a dendrogram, a tree-like diagram that shows the arrangement of clusters formed by the algorithm. Hierarchical clustering can be broadly classified into two types:

**Agglomerative (Bottom-Up):**

Start with each data point as its own cluster.
Merge the closest clusters iteratively until only one cluster remains (or the desired number of clusters is reached).
This is the most common approach.

**Divisive (Top-Down):**

Start with all data points in a single cluster.
Iteratively split clusters until each data point is in its own cluster.

**Key Steps in Agglomerative Hierarchical Clustering:**

1. Compute a similarity (or distance) matrix for all data points (e.g., using Euclidean distance).
2. Treat each data point as an individual cluster.
3. Merge the two clusters that are closest based on the similarity metric.
4. Update the similarity matrix to reflect the merging of clusters.
5. Repeat steps 3-4 until the stopping criterion (e.g., desired number of clusters) is reached.

Colab link: https://colab.research.google.com/drive/17qkEskyKwU3VE8fECMNqPyLqOw-hzU8Y#scrollTo=zjI3XWoyRqH8

Youtube link: https://youtu.be/AgcRgawpIKg
