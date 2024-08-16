Retail Store Sales Clustering using K-Means
Objective
The purpose of this project is to segment retail stores into distinct clusters based on their sales performance metrics. By using K-Means clustering, we aim to identify groups of stores that exhibit similar characteristics, which can provide valuable insights for targeted business strategies.

Dataset
The dataset used for this project is the Retail Store Sales Dataset, which contains various attributes of stores, such as:

StoreID
OperatingHours
StoreLocation
AnnualSales
NumberOfEmployees
MonthlyFootTraffic
CustomerSatisfactionScore
AverageTransactionValue
StoreSize
ProductVariety
Tasks
Data Preprocessing:

Handle missing values.
Normalize/scale numerical features to bring them to a common scale for K-Means.
Optimal Number of Clusters (Elbow Method):

Use the Elbow Method to identify the optimal number of clusters by plotting the within-cluster sum of squares (WCSS) against the number of clusters.
K-Means Clustering:

Apply the K-Means algorithm to the preprocessed data to cluster stores based on their sales performance metrics.
Visualization:

Visualize the resulting clusters using a scatter plot to display how stores are grouped based on their sales performance metrics.
Cluster Interpretation:

Analyze the characteristics of each cluster, focusing on key metrics such as AnnualSales, CustomerSatisfactionScore, MonthlyFootTraffic, and others to understand the performance of each group.
