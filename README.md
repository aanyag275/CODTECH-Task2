**Name:** AANYA GARG

**Company:** CODTECH IT SOLUTIONS  

**ID:** CT6WDS202

**Domain:** Data Analytics  

**Duration:** June to July 2024  

**Mentor:** MOHAMMED MUZAMMIL AHMED


## Overview of the Project

### Project: CUSTOMER SEGMENTATION AND ANALYSIS
![download](https://github.com/user-attachments/assets/90255dfc-5d51-43c9-acdd-4c6cd1753c52)
![download (1)](https://github.com/user-attachments/assets/f837419f-53b2-49b2-82e0-adbd861eeca5)
![download (3)](https://github.com/user-attachments/assets/c52b592c-6ed9-4701-ae61-9c1540393a2f)


### Objective
The objective of this task is to perform customer segmentation analysis on a retail dataset using clustering techniques like K-means or DBSCAN.

### Data Loading and Preprocessing:
- Load the retail dataset and preprocess it to derive relevant features like TotalAmount from Quantity and UnitPrice.
- Convert InvoiceDate to datetime format and aggregate data by CustomerID to compute metrics like Frequency, TotalAmount, and Recency.
### Feature Selection and Normalization:
- Select features (Frequency, TotalAmount, Recency) for segmentation.
- Normalize the selected features using StandardScaler to ensure uniform scale across different metrics.
### Determining Optimal Number of Clusters:
- Use the elbow method to determine the optimal number of clusters (optimal_clusters) for K-means clustering based on within-cluster sum of squares (WCSS).
### Applying K-means Clustering:
- Apply K-means clustering with the determined optimal number of clusters (optimal_clusters) to segment customers based on their normalized features.
### Analyzing and Visualizing Segments:
- Compute cluster summaries to analyze segment characteristics (mean Frequency, TotalAmount, Recency for each cluster).
- Visualize customer segments using scatter plots to show relationships between TotalAmount vs. Frequency and Recency vs. Frequency, colored by cluster.

### Technologies Used
- **Python**: The primary programming language for data analysis.
- **pandas**: Used for data manipulation and analysis.
- **matplotlib**: Employed for creating static, animated, and interactive visualizations.
- **sklearn**: User for preprocessing and k-means clustering.
- **seaborn**: Utilized for making statistical graphics that are informative and attractive.

The outcome of this analysis should provide actionable insights into customer segments within the retail dataset. These insights can be used to tailor marketing strategies, optimize inventory management, and enhance customer retention efforts based on the distinct behaviors and characteristics identified within each segment.
