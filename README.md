**CryptoClustering**

Thisproject examines the unsupervised learning methods using K-means and PCA (Principal Component Analysis) to analyze crpto currency data to predict 24-hours and 7-days price analysis.

Using StandardScaler to normalize CSV data follwed up by  creating a dataframe for the scaled data using "coin_id" as index. 

Finding optimal by using the elbow method on both original scaled data and PCS data to find the best K value. 

By using the initial scaled data to find the best way to group it into cluster. This would be followed by adding clusters grouping to the data. A scatter plot is then initiallized by using 2 specific information PC1 & PC@ with ewach cluster group shown in different color.

The grouping is repeated using the same process to see if any changes occured. this would be made into another scatter plot to find the diffrence. 

Objectives: Explore the impact of feature reduction on clustering. Practice identifying the optimal number of clusters using the elbow method. Gain experience with K-means clustering on datasets with both full and reduced dimensions.
