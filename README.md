# NASDAQ-STOCK-MARKET-CLUSTERING
NASDAQ Stock Marketing Clustering using K-Means Clustering

This machine learning project is about clustering similar companies with K-means clustering algorithm. The similarity is based on their annual performance.So basically the stocks are grouped according to their annual return and volatility.Here we have taken over 200 companies listed on the NASDAQ stock exchange into consideration.

# Data

The information such as opening and closing prices,Highs and Lows and Volumes of over 200 Companies listed on NASDAQ were scrapped from Yahoo Finance using the yfinance api.

# Environment and tools

1.Scikit-Learn

2.Plotly

3.Numpy

4.Pandas

5.Matplotlib

# K-Means Clustering Algorithm

1.Specify number of clusters K.

2.Initialize centroids by first shuffling the dataset and then randomly selecting K data points for the centroids without replacement.

3.Keep iterating until there is no change to the centroids. i.e assignment of data points to clusters isn’t changing

# Tasks Performed

1.Scrapped the data of 200 companies listed on NASDAQ from Yahoo Finance and created the dataset

2.Peformed visualization and analysis to get a clear picture of the data

3.Determined the appropriate value of K using elbow method and calculated the Within-Cluster-Sum-of-Squares (WCSS)

4.Clustered the data set based on annual performance by using K-means Clustering from the Sk-Learn library

5.Implemented the K-means algorithm from scratch and compared the result with the predefined Sk-Learn library.


