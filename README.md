# Unsupervised-machine-learning-challenge
# Cryptocurrency Clusters
Background

- Using several clustering algorithms to explore whether the cryptocurrencies can be grouped together with other similar cryptocurrencies. 


## Data Preparation
The dataset was obtained from CryptoCompare.

- Filter for currencies that are currently being traded.

- Remove all rows that have at least one null value.

- Filter for cryptocurrencies that have been mined. That is, the total coins mined should be greater than zero.

- Delete the CoinName from the original dataframe.

- Convert the remaining features with text values, Algorithm and ProofType, into numerical data. 

- Standardize the dataset so that columns that contain larger values do not unduly influence the outcome.

## Dimensionality Reduction
- Creating dummy variables above dramatically increased the number of features in the dataset. 
- Perform dimensionality reduction with PCA.
- Reduce the dataset dimensions with t-SNE and visually inspect the results. 

## Cluster Analysis with k-Means
- Create an elbow plot to identify the best number of clusters. 



































