# Customer Segmentation Analysis 
## Introduction   
This repository contains code for a customer segmentation analysis aimed at assisting a supermarket in increasing their membership card conversion rate. The analysis involves exploring different clustering techniques to identify similar groups of customers based on shopping preferences and purchasing history. This README file provides an overview of the code and its purpose.

## Data Overview
The dataset used in this analysis consists of information related to 200 customers. Each customer has attributes such as age, gender, annual income, and spending score. The spending score is a numeric variable ranging from 1 to 100, assigned based on customer behavior and purchasing data. The dataset also includes a customer ID column, which is dropped before the analysis.

## Code Overview
The code in this repository performs a comprehensive customer segmentation analysis using three clustering techniques: K-Means Clustering, Hierarchical Clustering, and DBSCAN. The analysis includes the following steps:

* Data Preprocessing: The data is loaded and basic data cleaning and renaming are performed.
* Exploratory Data Analysis (EDA): Visualizations are created to explore the relationships between customer attributes, including age, gender, annual income, and spending score.
* K-Means Clustering: The optimal number of clusters is determined using the elbow method. K-Means clustering is then applied, and the results are visualized.
* Hierarchical Clustering: Hierarchical clustering is performed using complete linkage. The dendrogram is plotted, and clusters are visualized.
* DBSCAN: Density-Based Spatial Clustering is applied using DBSCAN. The clusters are visualized along with outliers.
* Cluster Profile Comparison: The customer profiles based on age, income, and spending for each clustering model are visualized using 3D scatterplots.

## Conclusion  
This customer segmentation analysis provides valuable insights into the types of customers the supermarket serves and offers recommendations for targeted marketing strategies. By understanding customer behavior and preferences, the supermarket can tailor their promotions and offerings to different customer segments, ultimately increasing the membership card conversion rate. Further improvements and enhancements can be made by incorporating additional data and exploring advanced clustering techniques.
