Retail Store Sales Clustering using K-Means
Objective
This project segments retail stores into distinct clusters based on their sales performance using the K-Means clustering algorithm. The goal is to identify similar store groups, providing insights into business strategy and performance optimization.

Dataset
The dataset used is the Retail Store Sales Dataset with the following columns:

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
Project Overview
Data Preprocessing:

Handled missing values by imputing them where necessary.
Normalized all numerical features, such as AnnualSales, CustomerSatisfactionScore, MonthlyFootTraffic, etc., to ensure consistency in the K-Means algorithm.
Optimal Number of Clusters (Elbow Method):

Applied the Elbow Method to determine the optimal number of clusters. This involved plotting the within-cluster sum of squares (WCSS) for various cluster counts and identifying the "elbow" point.
K-Means Clustering:

Implemented the K-Means clustering algorithm on the preprocessed data to segment the retail stores into clusters.
Cluster Visualization:

Visualized the clusters using a scatter plot. The clusters were distinguished by color, showcasing how different stores group together based on performance metrics.
Cluster Interpretation:

Examined the characteristics of each cluster by focusing on key performance metrics such as AnnualSales, CustomerSatisfactionScore, MonthlyFootTraffic, and more.
Summarized the performance traits for each group of stores.
