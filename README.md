# CryptoClustering
 week 19 challenge

The objective of this challenge was to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

## Steps
Detailed steps can be found in the Jupyter Notebook. Below is the general steps taken to complete the challenge:

1. Prepare the data. This includes using StandardScaler() to normalize the data, and creating a new DataFrame with the scaled data.
2. Find the best value for k using the original scaled DataFrame. I used the Elbow Method.
3. Cluster cryptocurrencies with K-means using the original scaled data.
4. Optimize clusters with Principal Component Analysis (PCA).
5. Find the best value for k using the PCA data.
6. Cluster cryptocurrencies with K-means using the PCA data.
7. Create composite plots to compare the visualizations prepared in above steps.
