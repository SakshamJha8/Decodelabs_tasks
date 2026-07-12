\# Customer Segmentation using K-Means Clustering



This project was completed as Task 3 of my Data Science Internship at Decodelabs. The objective was to perform Customer Segmentation using Unsupervised Machine Learning techniques. By analyzing customer demographics and purchasing behavior, the project identifies distinct customer groups that can help businesses design targeted marketing strategies and improve customer engagement.



\---



\# Objectives



\- Perform data preprocessing and cleaning

\- Engineer meaningful features from the dataset

\- Reduce dimensionality using Principal Component Analysis (PCA)

\- Determine the optimal number of clusters using the Elbow Method and Silhouette Score

\- Segment customers using the K-Means clustering algorithm

\- Visualize customer segments in a 2D feature space

\- Translate clustering results into actionable business insights



\---



\# Dataset



Dataset: marketing\_campaign.csv



The dataset contains customer demographic information, income, spending habits, purchase history, and campaign responses.



\# Key Features



\- Age

\- Income

\- Education

\- Marital Status

\- Number of Children

\- Product Spending

\- Purchase Frequency

\- Web Purchases

\- Catalog Purchases

\- Store Purchases

\- Website Visits



\---



\# Tools Used



\- Python

\- Pandas

\- NumPy

\- Matplotlib

\- Seaborn

\- Scikit-learn



\---



\#Project Workflow



1\. Data Preprocessing



\- Loaded the dataset

\- Checked data types and missing values

\- Filled missing values

\- Removed unnecessary columns

\- Encoded categorical variables



2\. Feature Engineering



Created new features including:



\- Age

\- Total Spending

\- Children

\- Family Size



3\. Data Standardization



Standardized numerical features using StandardScaler to ensure equal contribution during clustering.



4\. Principal Component Analysis (PCA)



Reduced the dataset to two principal components for easier visualization while preserving the majority of the information.



5\. Finding the Optimal Number of Clusters



Used:



\- Elbow Method

\- Silhouette Score



to identify the optimal value of K.



6\. K-Means Clustering



Applied the K-Means algorithm to segment customers into meaningful groups.



7\. Cluster Analysis



Analyzed each customer segment based on spending behavior and demographic characteristics.



\---



\#Visualizations



The project includes several visualizations such as:



\- Correlation Heatmap

\- PCA Projection

\- Elbow Method Curve

\- Silhouette Score Curve

\- Customer Cluster Visualization

\- Cluster-wise Spending Analysis

\- Income Distribution by Cluster



\---



\# Customer Personas



Based on the clustering results, customers were categorized into different groups, such as:



\# Premium Customers

\- High income

\- High spending

\- Frequent purchases



\# Business Strategy

\- Exclusive rewards

\- Premium memberships

\- Personalized recommendations



\---



\# Budget Customers

\- Lower spending

\- Price-sensitive

\- Infrequent purchases



\# Business Strategy

\- Discount campaigns

\- Coupons

\- Bundle offers



\---



\# Family Shoppers

\- Medium spending

\- Family-oriented purchases

\- Regular buyers



\# Business Strategy

\- Family packages

\- Loyalty programs

\- Seasonal promotions



\---



\# Digital Customers

\- High online purchases

\- Active website users

\- Prefer digital shopping



\# Business Strategy

\- Personalized email campaigns

\- Mobile app offers

\- Online-exclusive discounts



\---



\# Model Evaluation



The clustering performance was evaluated using:



\- Elbow Method

\- Silhouette Score



These techniques helped identify the optimal number of customer segments while ensuring meaningful separation between clusters.



\---



\# Results



\- Successfully reduced the dataset dimensions using PCA.

\- Identified the optimal number of customer segments using the Elbow Method and Silhouette Score.

\- Built a K-Means clustering model to classify customers into distinct groups.

\- Generated business-focused customer personas to support targeted marketing strategies.



\---

\# ***Author***



***Saksham Jha***

***B.Tech in (AI\&DS)***





