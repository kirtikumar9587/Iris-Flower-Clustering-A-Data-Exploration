# Iris-Flower-Clustering-A-Data-Exploration
Unsupervised machine learning is a type of machine learning where the model is not trained on labeled data but rather on raw, unlabeled data. K-means clustering is a popular unsupervised machine learning algorithm that is used for clustering and segmentation of data.

The k-means algorithm is an iterative algorithm that aims to partition a set of data points into k clusters. The algorithm starts by randomly selecting k initial cluster centroids and assigns each data point to its nearest centroid. Then, it iteratively updates the centroids and re-assigns the data points to their nearest centroid until the convergence criteria are met.

One application of k-means clustering is for prediction. Given a new data point, the k-means algorithm can be used to predict which cluster it is likely to belong to based on the cluster centroids and the distances between the data point and the centroids.

To make a prediction using k-means clustering, first, the trained model is used to obtain the cluster centroids. Then, the distance between the new data point and each of the centroids is calculated. The data point is assigned to the cluster with the nearest centroid.

It is important to note that k-means clustering is an unsupervised algorithm and does not rely on labels for training or prediction. Therefore, the quality of the prediction depends on the quality of the clustering, which in turn depends on the quality and relevance of the features used in the clustering.
