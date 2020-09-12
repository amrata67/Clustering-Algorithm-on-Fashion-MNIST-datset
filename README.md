# Analysing Clustering Algorithms on Fashion MNIST datset

This project provides the clear understanding of features of unsupervised learning. We can see the performance difference between K-Mean clustering and Gaussian Mixture Matrix Clustering on Fashion MNIST dataset to classify datapoints into 10 clusters. An autoencoder lets us re-represent high dimensional points in a lower-dimensional space called as 'latent space'. We use this reduced dimensional representation for clustering. We can notice the accuracy improving over baseline K-means algorithm when we use Autoencoding and GMM clustering.
 
 ## Introduction
In this project, we classify the datasets of Fashion MNIST into 10 clusters. Clustering is the process of grouping the datapoints into several groups called Clusters such that data points in same group are similar to each other. This determines intrinsic grouping among unlabeled dataset. We used Autoencoder to reduce the dimensionality of dataset to get better accuracy in clustering. This lower dimensional space is called as Latent Space. For clustering purpose, we use this dataset in latent space to improve on accuracy.
A Gaussian mixture model is a probabilistic model that assumes all the data points are generated from a mixture of a finite number of Gaussian distributions with unknown parameters. One can think of mixture models as generalizing k-means clustering to incorporate information about the covariance structure of the data as well as the centers of the latent Gaussians.


