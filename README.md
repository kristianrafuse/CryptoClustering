Unsupervised-Machine-Learning
-------

In this example of unsupervised machine learning, I use Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes. I used a variety of tools including StandardScaler, K-means Modelling, Clustering with Principal Component Analysis, and hvPlot. 

Highlights:
-------
* Code the elbow method algorithm to find the best value for k.
* Visually identify the optimal value for k, plot a line chart of all the inertia values computed with the different values of k.
* Initialize the K-means model with four clusters by using the best value for k.
* Fit the K-means model by using the original data.
* Predict the clusters for grouping the cryptocurrencies by using the original data.
* Using hvPlot, create a scatter plot, color the graph points with the labels found by using K-means, add the crypto name to the hover_cols parameter to identify the cryptocurrency that each data point represents.

Principal Component Analysis:
-------
* Use the PCA model to reduce the features to three principal components.
* Get the explained variance to determine how much information can be attributed to each principal component.
* Initialize the K-means model with four clusters by using the best value for k.
* Fit the K-means model by using the PCA data.

HVPlot:
-------
* Create a composite plot by using hvPlot to compare the elbow curve that you created from the original data with the one from the PCA data.
* Create a composite plot by using hvPlot to compare the cryptocurrency clusters that resulted from using the original data with those that resulted from the PCA data.
