This project applies K-Means clustering to a dataset of cryptocurrencies to analyze patterns and group 
similar cryptocurrencies. The analysis is performed both with the original features and after reducing 
dimensionality using Principal Component Analysis (PCA).

The data is scaled using StandardScaler for normalization.

PCA is applied to reduce the dataset to three principal components while retaining most of the variance.

The elbow method is used to determine the optimal number of clusters (k=4) for both the original dataset
and the PCA-transformed dataset.

K-Means clustering is applied to group cryptocurrencies based on their features.

Scatter plots used to visualize the results and compare the original dataset to the PCA-transformed dataset.

The optimal number of clusters was consistent across both the original and PCA-transformed datasets.

PCA reduced the number of features while preserving clustering patterns making the data easier to read and
analyze.

All code assembled by myself, Rebekkah Alexander, using class notes and ChatGPT 4.0.
