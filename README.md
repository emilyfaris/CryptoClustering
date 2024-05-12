# Cryptocurrency Clustering Project

## Overview
This project explores clustering techniques applied to cryptocurrency data using K-Means and Principal Component Analysis (PCA). The aim is to identify optimal clusters and understand the underlying patterns in cryptocurrency data.

## Project Steps

### Data Preprocessing
- **Normalization**: Utilized `StandardScaler` from scikit-learn to scale the data.

### Optimal Cluster Identification
- **Elbow Method**: Used the elbow method to determine the optimal number of clusters.

### Clustering with K-Means
- **K-Means Clustering**: Clustered cryptocurrencies using the optimal k identified from the original scaled data.
- **Visualization**: Created scatter plots using hvPlot to visualize clusters based on PCA components and original features.

### PCA Optimization
- **PCA Application**: Reduced the feature space using PCA to three principal components.
- **Variance Analysis**: Analyzed the explained variance to assess information retention.
- **Re-clustering**: Applied the elbow method again on PCA-reduced data to compare with the original data clustering.

### Results
- **Cluster Interpretation**: Examined how cluster characteristics vary with the number of features.
- **Impact Analysis**: Discussed the impact of using fewer features on the clustering results.

## Technologies Used
- Python
- Pandas
- scikit-learn
- hvPlot

## Conclusion
This project provided insights into the clustering of cryptocurrencies and demonstrated the effectiveness of dimensionality reduction with PCA in simplifying complex clustering tasks.

