**K-Means Clustering Analysis**

**Overview:**

The goal of this project is to analyze the performance of the K-Means clustering algorithm on datasets with distinct characteristics. For the Iris dataset, we aim to group data points based on selected features, while for the handwritten images dataset, we explore clusters in high-dimensional pixel data.

**Features:**

* Preprocessing of datasets, including scaling and feature selection  
* Clustering using K-Means with KMeans++ for centroid initialization  
* Dimensionality reduction with t-SNE for visualization  
* Determination of optimal cluster count using the Elbow Method  
* Visualization of Sum of Squared Errors (SSE) across varying cluster numbers  
* Recording of final cluster assignments for both datasets

**Datasets:**

1. Iris Dataset  
* Features: ‘petal length (cm)’ and ‘petal width (cm)’  
* Optimal clusters: K=3  
* Visualization using pair plots for feature distribution

2. Handwritten Images Dataset  
* High-dimensional pixel data  
* Dimensionality reduction using t-SNE for effective clustering  
* Optimal clusters: K=10

**Implementation Details:**

**K-Means Clustering**

* Initialization: Centroids are initialized using the KMeans++ algorithm for better convergence.  
* Cluster Assignment: Data points are assigned to the nearest cluster using Euclidean distance.  
* Centroid Update: Centroids are recalculated iteratively.  
* SSE Calculation: The Sum of Squared Errors is computed for evaluating clustering performance.

**Elbow Method:**

To determine the optimal K value, the Elbow Method iterates through K values from 2 to 20 (even numbers) and calculates SSE for each.

**Visualization**

* Pair plots for the Iris dataset  
* t-SNE plots for handwritten images  
* SSE vs. Number of clusters

**Results**

* Iris Dataset**: Achieved clustering with K=3. SSE plots helped confirm the optimal K.

* Handwritten Images Dataset**: Clustering finalized with K=10 after t-SNE dimensionality reduction.


