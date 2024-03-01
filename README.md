# Factor Analysis and K-Means Clustering

This repository contains code for conducting Factor Analysis and K-Means Clustering on a dataset related to customer satisfaction with airline services. The code is implemented in Python using various libraries such as pandas, numpy, matplotlib, seaborn, statsmodels, scikit-learn, and factor_analyzer.

# Introduction
Factor Analysis is a statistical method used to uncover underlying factors or latent variables within a dataset. It helps in understanding the structure of the data and identifying patterns among variables. K-Means Clustering is an unsupervised learning algorithm used for grouping data into clusters based on similarities.

# Factor Analysis
## Bartlett's Test of Sphericity and KMO Test
The code begins by performing Bartlett's Test of Sphericity and the Kaiser-Meyer-Olkin (KMO) Test to assess the suitability of the dataset for Factor Analysis. These tests evaluate whether the variables in the dataset exhibit significant dependencies and share common variance.

## Standardization and Principal Component Analysis (PCA)
The dataset is standardized using StandardScaler, and Principal Component Analysis (PCA) is performed to decide the number of factors to retain. The cumulative explained variance and scree plot inspection are used for this purpose.

## Factor Analysis Types
The code then conducts Factor Analysis with different rotation methods, including None, Promax, Quartimax, Orthogonal, and Varimax. The loadings for each factor are analyzed to understand the underlying structure of the data.

# K-Means Clustering
The code also includes K-Means Clustering to group the data into clusters based on customer satisfaction attributes. The elbow method is used to determine the optimal number of clusters, and the silhouette score is calculated to evaluate the clustering performance.

# Usage
To use this code, follow these steps:
1. Clone the repository to your local machine.
2. Install the required dependencies listed in the `requirements.txt` file.
3. Run the provided Jupyter Notebook or Python script to perform Factor Analysis and K-Means Clustering on your dataset.

# Conclusion
Factor Analysis and K-Means Clustering are powerful techniques for extracting insights and identifying patterns in complex datasets. By applying these methods, businesses can gain valuable insights into customer preferences and behavior, enabling them to make data-driven decisions to improve their services and products.
