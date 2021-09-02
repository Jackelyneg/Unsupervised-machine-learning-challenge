# Unsupervised-machine-learning-challenge
# Cryptocurrency Clusters
Background
You are on the Advisory Services Team of a financial consultancy. One of your clients, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. They’ve asked you to create a report that includes what cryptocurrencies are on the trading market and determine whether they can be grouped to create a classification system for this new investment.

You have been handed raw data, so you will first need to process it to fit the machine learning models. Since there is no known classification system, you will need to use unsupervised learning. You will use several clustering algorithms to explore whether the cryptocurrencies can be grouped together with other similar cryptocurrencies. You will use data visualization to share your findings with the investment bank.


## Data Preparation
The dataset was obtained from CryptoCompare.

- Filter for currencies that are currently being traded.

- Remove all rows that have at least one null value.

- Filter for cryptocurrencies that have been mined. That is, the total coins mined should be greater than zero.

- Delete the CoinName from the original dataframe.

- Cnvert the remaining features with text values, Algorithm and ProofType, into numerical data. 

- Standardize the dataset so that columns that contain larger values do not unduly influence the outcome.

## Dimensionality Reduction
- Creating dummy variables above dramatically increased the number of features in the dataset. 
- Perform dimensionality reduction with PCA.
- Reduce the dataset dimensions with t-SNE and visually inspect the results. 

## Cluster Analysis with k-Means
- Create an elbow plot to identify the best number of clusters. 



































