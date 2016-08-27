# Kmeans-clustering
Implementation of clustering algorithm in Python

Algorithms - 

K-means - 
  Initialize Cluster Centroids Randomly μ1, μ2, … , μn 
  Repeat until convergence
    For each data point i : 
      Find closest centroid and assign that data point to that cluster
    For each cluster
      Recalculate the value of centroid and update it		

Un-optimized K-means - 
  Convergence when no data point migrates

Optimized K-means - 
  Convergence when each centroid point moves no more than cut-off value

K-means++ - 
  Centroids are not initialized randomly, but instead determined by running optimized k-means on a training data

