# Gaussian Mixture Models (GMM) clustering

Gaussian Mixture Models (GMM) clustering is a soft clustering algorithm that assumes the data is generated from a mixture of several Gaussian distributions. Unlike K-Means, which assigns each data point to a single cluster (hard clustering), GMM calculates the probability of each data point belonging to every cluster and assigns it accordingly.

How GMM Works:

1. The algorithm starts by initializing parameters for each cluster, such as the center (mean), the spread (covariance), and the proportion of data points belonging to each cluster (mixing coefficients).
2. In the E-Step (Expectation), GMM calculates the probability of each data point belonging to every cluster based on the current parameters.
3. In the M-Step (Maximization), it updates the cluster parameters to maximize the likelihood of the observed data.
4. These two steps are repeated until the parameters stabilize, indicating convergence.
5. Finally, data points are assigned to clusters based on their probabilities, or the probabilities themselves can be used for further analysis.


Colab link: https://colab.research.google.com/drive/1U9LCTil-Yb58zHs_0gn1vQ1Avg6vWlsk?usp=sharing

Youtube link: https://youtu.be/8JNc34tBHEM
