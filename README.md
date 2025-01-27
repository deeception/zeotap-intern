Customer Segmentation using Clustering - Zeotap Assignment
About Zeotap
Zeotap is a global customer intelligence platform that provides brands with a unified view of their customers and enhances their marketing and customer engagement strategies. Zeotap works with leading companies to leverage data-driven insights, helping them make smarter business decisions. Through advanced machine learning and data analytics, Zeotap assists businesses in personalizing customer experiences and targeting the right audiences.

Assignment Overview
This project was part of an assignment for Zeotap, where the task was to perform customer segmentation using clustering techniques. The objective was to identify different customer groups based on their transactional behaviors and demographics, which could help Zeotap's clients target specific customer segments with personalized marketing strategies.

Problem Statement:
Given a dataset of customers and their transaction details, the goal was to:

Perform data preprocessing and feature engineering.
Apply clustering algorithms to segment customers based on spending patterns, frequency of purchases, and other relevant factors.
Evaluate the clustering results using metrics such as the Davies-Bouldin index.
Provide actionable insights for business use cases such as targeted marketing or customer retention strategies.
Deliverables
Clustering Model:

The primary deliverable is a customer segmentation model based on clustering.
The dataset has been segmented into 4 clusters, with each cluster representing different customer behaviors.
Features used for clustering include total spend, average transaction value, frequency of purchases, quantity purchased, and region.
Clustering Metrics:

DB Index: Measures the validity of the clusters formed, with a lower value indicating better-defined clusters.
Cluster Summaries: Descriptions of each customer segment, including key metrics like total spend, frequency of purchases, and average transaction value.
Python Code:

The code includes data preprocessing steps, clustering model implementation (using K-Means clustering), and the calculation of relevant metrics.
Example code for creating, training, and evaluating the clustering model.
Data:

The input data contains customer transaction details (Customer ID, Product ID, Transaction Date, Quantity, Price, and Total Value), along with customer demographics (Region, Signup Date).
The data has been preprocessed to generate additional features like total spend, frequency of purchases, and average transaction values.
Results:

A summary of the clustering results, including insights into the customer segments.
The final output of customer segmentation has been saved in a CSV file for easy analysis.
Files in this Repository
customer_segmentation.py: The main Python script that performs all steps, from data preprocessing to clustering.
Customer_Segments.csv: Final dataset with customer segments.
README.md: This readme file with detailed project information.
requirements.txt: List of dependencies required to run the project.
