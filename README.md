<h1> Diabetes Prediction using K-means Clustering </h1>

In this article, we will cover k-means clustering from scratch. In general, Clustering is defined as the grouping of data points such that the data points in a group will be similar or related to one another and different from the data points in another group. The goal of clustering is to determine the intrinsic grouping in a set of unlabelled data.

K- means is an unsupervised partitional clustering algorithm that is based on grouping data into k – numbers of clusters by determining centroid using the Euclidean or Manhattan method for distance calculation. It groups the object based on minimum distance.

![Diabetes Prediction using Kmeans](https://aihubprojects.com/wp-content/uploads/2020/10/euclidean-distance-formula.png)

ALGORITHM

    1. First,  initialize the number of clusters, K (Elbow method is generally used in selecting the number of clusters )
    2. Randomly select the k data points for centroid. A centroid is the imaginary or real location representing the center of the cluster.
    3. Categorize each data items to its closest centroid and update the centroid coordinates calculating the average of items coordinates categorized in that group so far
    4. Repeat the process for a number of iterations till successive iterations clusters data items into the same group

HOW IT WORKS ?

In the beginning, the algorithm chooses k centroids in the dataset randomly after shuffling the data. Then it calculates the distance of each point to each centroid using the euclidean distance calculation method. Each centroid assigned represents a cluster and the points are assigned to the closest cluster. At the end of the first iteration, the centroid values are recalculated, usually taking the arithmetic mean of all points in the cluster.  In every iteration, new centroid values are calculated until successive iterations provide the same centroid value. 

[Read More  ...](https://aihubprojects.com/k-means-clustering-from-scratch-python/)
