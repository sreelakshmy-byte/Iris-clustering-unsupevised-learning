
Formative Assessment: Unsupervised Learning-IRIS Clustering
# Iris Dataset Clustering Project

## Overview

This project explores clustering techniques applied to the famous Iris dataset. The goal is to demonstrate how KMeans and Hierarchical Clustering algorithms can be used to group Iris flowers based on their features. The project includes the following components:

- **Data Preprocessing**: Scaling and handling missing values to prepare the data for clustering.
- **Outlier Detection and Removal**: Identifying and removing outliers to improve clustering accuracy.
- **Clustering Algorithms**:
  - **KMeans Clustering**: Groups the data into distinct clusters based on feature similarity.
  - **Hierarchical Clustering**: Builds a hierarchy of clusters and visualizes the merging process using a dendrogram.
- **Visualizations**:
  - Box plots, 3D scatter plots, and dendrograms to illustrate the clustering results.
  - Images of the three Iris species (Setosa, Versicolor, and Virginica) to provide a visual reference.

## Dataset

The Iris dataset consists of 150 samples of Iris flowers, with 4 features:

- **Sepal Length**
- **Sepal Width**
- **Petal Length**
- **Petal Width**

The dataset includes 3 different Iris species:

- **Setosa**
- **Versicolor**
- **Virginica**

The dataset is commonly used for classification and clustering tasks in machine learning and data analysis.

## Clustering Algorithms

### KMeans Clustering

KMeans is an iterative algorithm that divides the dataset into **K** distinct, non-overlapping clusters. The algorithm minimizes the squared distance between the data points and their respective cluster centroids. The KMeans algorithm assigns each data point to the nearest cluster, based on Euclidean distance. 

### Hierarchical Clustering

Hierarchical clustering builds a hierarchy of clusters by starting with each data point as its own cluster. It then iteratively merges the most similar clusters until all points are combined into a single cluster. This merging process can be visualized using a dendrogram, which helps to understand the data’s structure and determine the appropriate number of clusters.

## Visualizations

- **Box Plots**: Show the distribution of features across different clusters.
- **3D Scatter Plots**: Visualize the clustering in three dimensions to show how well the data points group together.
- **Dendrograms**: Illustrate the hierarchical clustering process, showing the distance between merged clusters.

Conclusion
This project demonstrates the application of KMeans and Hierarchical Clustering on the Iris dataset, providing valuable insights into the clustering process and how different algorithms can be applied to categorize flower species based on their physical features.

