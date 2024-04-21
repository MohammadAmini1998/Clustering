![298aa074-de39-4f9f-ae85-8f3d6c8928c3](https://github.com/MohammadAmini1998/Clustering/assets/49214384/49e44a0c-3229-412a-a005-6d92d5c18cb0)# Clustering Algorithms Implementation in Python

In this project, we implement several clustering algorithms and analyze the results using an artificial dataset.

### About Clustering

Clustering is a type of unsupervised learning technique used to group data points or objects that are similar to each other. It aims to partition data into groups or clusters such that data points in the same cluster are more similar to each other than to those in other clusters.

### K-Means Clustering Algorithm

The K-Means algorithm is one of the most popular clustering algorithms. It is an iterative algorithm that partitions the data into `k` clusters. The main idea behind K-Means is to minimize the sum of squared distances between data points and their corresponding cluster centroids. The algorithm works as follows:

1. **Initialization**: Randomly select `k` data points as the initial centroids.
2. **Assignment**: Assign each data point to the nearest centroid, forming `k` clusters.
3. **Update**: Recalculate the centroids of the clusters based on the mean of the data points assigned to each cluster.
4. **Repeat**: Repeat steps 2 and 3 until convergence, i.e., until the centroids no longer change significantly.

### Agglomerative Clustering Algorithm

Agglomerative clustering is a hierarchical clustering algorithm that follows a "bottom-up" approach. The algorithm starts by treating each data point as a single cluster and then iteratively merges the closest pairs of clusters until only one cluster remains. The main steps of the agglomerative clustering algorithm are as follows:

1. **Initialization**: Start with `n` clusters, each containing one data point.
2. **Compute Pairwise Distances**: Compute the distance between each pair of clusters.
3. **Merge Clusters**: Merge the two closest clusters.
4. **Update Distance Matrix**: Update the pairwise distance matrix.
5. **Repeat**: Repeat steps 2-4 until only one cluster remains.
### Dataset
The dataset used for this project consists of a number of artificial points created in the `artificial_data.txt` file. Each line in the file represents a point along with its class label. However, for the purpose of clustering, we only consider the coordinates of the points.
### Results


![Uploading 298aa074-de39-4f9f-ae85-8f3d6c8928c3.p![77e704f7-3934-42c3-a6ff-a39f14988df7](https://github.com/MohammadAmini1998/Clustering/assets/49214384/0d6a2be9-3fa5-47ab-83f6-27ae3069fcdf)
![ff096290-1e0b-4081-959a-80c07ee93d25](https://github.com/MohammadAmini1998/Clustering/assets/49214384/df02283f-1bdb-47e9-8d49-03cf259fd4bf)
![bd76ad12-64c7-4faf-97ef-ee1a089abf52](https://github.com/MohammadAmini1998/Clustering/assets/49214384/6aac6443-086d-445d-a439-0f88ef093cfb)
ng…]()
