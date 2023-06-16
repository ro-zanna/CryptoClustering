# CryptoClustering

In this assignment, we used unsupervised machine learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.
First we scaled the market data to convert it to numerical values for Pandas (preprocessing).
Then we calculated the inertia values of the data to plot an elbow curve to show the optimal number of clusters.
With a k value of 4, we used the k-means model to predict the clusters and plotted them in a scatter plot.
In the next section we applied the PCA to simplify the data into 3 components.
The explained variance ratio added up to 89% for the 3 components, which indicates a good fit between this model and dataset.
We then repeated the above steps, calculating inertia to find the k value and fitting the k-means model to cluster the PCA data.
The composite graphs show that PCA data predicts stock price changes better in real-time.
