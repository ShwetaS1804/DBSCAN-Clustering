
## Customer Grouping using DBSCAN Clustering
AI Analyst Project Submission
Team Details

- Member 1: Shweta Singh (202310101150047), B.Tech CSE (DS+AI)-52
- Member 2: Yashvi Jaiswal (202310101150020), B.Tech CSE (DS+AI)-51
## Problem Statement
# To group customers based on their annual income and spending score using DBSCAN clustering algorithm, and to understand their behaviors and preferences for targeted marketing.



     
## Dataset Details
We are using a synthetic dataset containing 200 samples with the following features:

Annual Income (k$)
Spending Score (1-100)
The data is generated to simulate different spending patterns of customers.

## Explanation of ML Model
DBSCAN (Density-Based Spatial Clustering of Applications with Noise) is a clustering algorithm that groups together points that are close to each other based on a distance measurement and a minimum number of points.

     
## Results and Insights
DBSCAN successfully identified clusters based on customer behavior.
It also labeled some customers as noise (outliers) who do not belong to any cluster.
This can help in identifying unique or extreme spending behaviors.

## Challenges Faced
Choosing the right eps and min_samples values is crucial and non-trivial.
DBSCAN may not perform well on datasets with varying densities.
## Learnings
Understood how density-based clustering works.
Learned to apply DBSCAN for customer segmentation.
Realized the importance of data scaling and parameter tuning.
