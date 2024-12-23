Clustering of Iris Dataset using KMeans and Hierarchical Clustering

Project Overview
This project demonstrates the application of two clustering algorithms, KMeans and Hierarchical Clustering, on the well-known Iris dataset. The objective is to group the data into clusters based on the features of the Iris flowers and visualize the results.

Dataset
The dataset used in this project is the Iris dataset, which consists of 150 observations of iris flowers, with 4 features:

Sepal length (cm)
Sepal width (cm)
Petal length (cm)
Petal width (cm)
The dataset is widely used for machine learning tasks, especially clustering and classification.

Libraries Used
numpy for numerical operations
pandas for data handling
matplotlib and seaborn for data visualization
sklearn for clustering algorithms and data preprocessing
scipy for hierarchical clustering
Steps
Loading and Preprocessing Data:

The Iris dataset is loaded using sklearn.datasets.load_iris().
Missing values and duplicates are handled.
Boxplots are used to visualize any outliers.
Skewness and kurtosis are calculated for each feature.
Scaling the Data:

The data is scaled using StandardScaler to normalize the features before clustering.
KMeans Clustering:

The KMeans algorithm is applied to the scaled data.
The optimal number of clusters is determined using the Elbow Method.
Clusters are visualized using a scatter plot, with centroids marked.
Hierarchical Clustering:

Agglomerative Clustering is applied to the dataset.
The results are visualized using a scatter plot.
A Dendrogram is created to visualize the merging of clusters, helping to decide the optimal number of clusters.
Key Outputs
KMeans Clustering Visualization: A scatter plot showing the data points colored by cluster, with red X markers for centroids.
Elbow Method Visualization: A plot showing inertia vs. number of clusters to identify the optimal number of clusters.
Hierarchical Clustering Visualization: A scatter plot showing clusters formed using Agglomerative Clustering.
Dendrogram: A plot showing the hierarchical structure of the clusters, with a threshold line to decide on the optimal cutoff.
Clustering Results
KMeans Clustering: Identifies 3 clusters based on the Iris flower features.
Hierarchical Clustering: Also identifies 3 clusters, with a dendrogram showing how the clusters are merged.
Conclusion
Both KMeans and Hierarchical Clustering were applied to the Iris dataset. The clustering results demonstrate that the Iris flowers can be grouped into 3 distinct clusters. The Elbow Method helped to determine the optimal number of clusters for KMeans, while the Dendrogram provided a clear view of the hierarchical structure of the dataset.
