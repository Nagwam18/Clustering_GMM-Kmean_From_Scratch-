Clustering Algorithms from Scratch: K-Means & Gaussian Mixture Model (GMM)
This repository contains Python implementations of two popular clustering algorithms: K-Means and Gaussian Mixture Models (GMM). Both algorithms are implemented from scratch using NumPy for matrix operations, without relying on any machine learning libraries such as Scikit-learn.

📂 Folder Structure
graphql
Copy
Edit
clustering_from_scratch/
├── kmeans.py          # K-Means clustering algorithm implementation
├── gmm.py             # Gaussian Mixture Model (GMM) implementation
├── utils.py           # Utility functions (e.g., data generation, visualization)
├── main.py            # Example usage of K-Means and GMM on sample datasets
├── requirements.txt   # Required Python packages for running the project
└── README.md          # Project README file
🧑‍💻 Project Description
In this project, we implement the K-Means and Gaussian Mixture Model (GMM) algorithms from scratch. These are unsupervised learning techniques used for clustering tasks. The purpose of this repository is to demonstrate how these algorithms work internally by coding them from scratch and applying them on real-world datasets.

Key Concepts
K-Means: A partitioning clustering algorithm that tries to group data into k clusters by minimizing the variance within each cluster. It works by iteratively assigning data points to the nearest cluster center and updating the cluster centers until convergence.

Gaussian Mixture Models (GMM): A probabilistic model that assumes that data points are generated from a mixture of several Gaussian distributions. It estimates the parameters of these Gaussian distributions (mean, covariance, and weight) using the Expectation-Maximization (EM) algorithm.

🧩 Features
K-Means Implementation: Includes:

Initialization of centroids

Assignment of points to the nearest centroids

Update of centroids based on point assignments

Convergence criteria to stop the algorithm

Gaussian Mixture Model (GMM): Includes:

Expectation-Maximization (EM) algorithm

Estimation of means, covariances, and weights of Gaussian distributions

Soft assignment of data points to clusters based on probabilities

