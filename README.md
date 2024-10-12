# Mall-Customers-Clustering-and-PCA-Analysis
This repository contains a project that performs customer segmentation using clustering techniques and Principal Component Analysis (PCA) on the Mall Customers Dataset. The objective is to group customers into clusters based on their annual income and spending behavior and apply PCA to reduce dimensionality for better visual insights.

## Overview
This project aims to segment mall customers based on their spending behavior and income using Agglomerative Clustering. Additionally, PCA is employed for dimensionality reduction to visualize the data in lower-dimensional space. The clustering results are used to identify patterns in customer behavior, which can help businesses tailor their strategies for different customer groups.

## Key Features:
* Clustering: Agglomerative clustering with Ward's linkage method for customer segmentation.
* PCA: Dimensionality reduction to identify key components that explain the variance in customer data.
* Data Visualization: Dendrogram, 2D, and 3D scatter plots to visualize clusters and principal components.

## Dataset
The Mall Customers Dataset consists of 200 observations with 5 features:
* CustomerID: Unique identifier for each customer.
* Genre: Gender of the customer (Male/Female).
* Age: Age of the customer.
* Annual Income (k$): Annual income of the customer in thousands of dollars.
* Spending Score (1-100): A score assigned by the mall based on customer behavior and spending.

## Data Preprocessing
The dataset is first explored, cleaned, and normalized to ensure that the clustering algorithm works effectively:
* Exploratory Data Analysis: Summary statistics, checking for missing values, and duplicates.
* Feature Selection: Focused on the Annual Income (k$) and Spending Score (1-100) for clustering.
* Normalization: Applied MinMax scaling to normalize the range of income and spending score.

## Clustering
* **Agglomerative Clustering:**
We apply Agglomerative Clustering with Ward's method to group customers into 5 clusters. A dendrogram is used to visualize the clustering hierarchy and help determine the optimal number of clusters.

## Principal Component Analysis (PCA)
To reduce the dimensionality of the dataset, we apply PCA and visualize the data in 2D and 3D space.

## Results
* **Clustering Insights:**
  * The Agglomerative Clustering algorithm segmented the customers into 5 distinct groups based on their income and spending scores. These clusters can be interpreted for customer behavior insights, which may help in marketing strategies.

* **PCA Insights:**
  * PCA reduced the dataset dimensions while maintaining most of the data's variance. The first few principal components explain a significant amount of variance, allowing for a simplified view of the dataset without losing much information.

## Conclusion
This project demonstrates customer segmentation using Agglomerative Clustering and dimensionality reduction using PCA. The results highlight clear clusters of customer behavior, and the PCA analysis provides a lower-dimensional representation for easier interpretation.
