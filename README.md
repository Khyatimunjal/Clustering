# Clustering

## Dataset
The dataset used for this project is Iris Dataset, a commonly used dataset in machine learning. It contains 150 samples of iris flowers, each with four features: sepal length, sepal width, petal length, and petal width.

## Clustering Algorithms
1. K-Means Clustering: A centroid-based clustering algorithm that partitions data into K clusters by iteratively assigning each data point to the nearest centroid.
2. Hierarchical Clustering: A bottom-up clustering algorithm that builds a hierarchy of clusters by successively merging or splitting clusters.
3. K-Means Shift Clustering: A density-based clustering algorithm that identifies clusters as high-density regions separated by low-density regions.

## Preprocessing Techniques
1. Normalization: Scaling numerical features to a common range, typically [0, 1] or [-1, 1].
2. Transformation: Applying transformations such as Yeo-Johnson to make data distributions more Gaussian-like.
3. Principal Component Analysis (PCA): Reducing the dimensionality of data by projecting it onto a lower-dimensional subspace while preserving the maximum variance.

## Evaluation Parameters
1. Silhouette Score: A measure of how similar an object is to its cluster compared to other clusters.
2. Calinski-Harabasz Index: A ratio of the between-cluster dispersion and within-cluster dispersion.
3. Davies-Bouldin Index: A measure of the average 'similarity' between each cluster, where similarity is the ratio of within-cluster distances to between-cluster distances.

## Results
The results of the clustering analysis are summarized through tables, graphs, highlighting the performance of each clustering algorithm under different preprocessing techniques and numbers of clusters.

## Conclusion
The project concludes with insights drawn from the analysis, discussing the effectiveness of different clustering algorithms and preprocessing techniques in identifying meaningful clusters within the Iris dataset.
