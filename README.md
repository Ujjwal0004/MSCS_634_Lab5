# MSCS_634_Lab5

# Lab 5: Hierarchical and DBSCAN Clustering

## Purpose

The purpose of this lab is to demonstrate clustering techniques by analyzing the wine data set found within the sklearn library. By utilizing Hierarchical Clustering and DBSCAN, the goal of this lab is to determine the grouping of similar data points through the application of these clustering techniques and gain an understanding of the differences between various clustering techniques. Evaluation of the clustering results included Silhouette Score, Homogeneity Score, and Completeness Score along with visualizations of the clusters formed.


## Key Insights

- Hierarchical clustering grouped wine sample based on similarities in their feature values.
- A dendrogram was used to visualize how clusters merged based on distance level.
- Changing the value of n_clusters resulted in the formation of different cluster groupings within hierarchical clustering.
- DBSCAN grouped data points based on density and identified noise points that did not fit into any of the clusters.
- Evaluation Metrics such as Silhouette Score, Homogeneity Score, and Completeness Score, allowed for the measurement of the quality of the clustering and comparison of the results from the clustering techniques.

## Challenges

- Finding the correct combination of parameters such as eps and min_samples for DBSCAN took multiple trials and errors.
- Using some of the parameter combinations created either too many noise points or too few clusters.
- Selecting two features to display clustering results limited the ability to fully visualize the results of the clustering.
- Careful observation of both the plots and the evaluation metrics was needed to understand the impact of changing parameters on the clustering results.
