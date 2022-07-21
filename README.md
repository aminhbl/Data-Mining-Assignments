<div id="top"></div>

<br />
<div align="center">

<h2 align="center">Data Mining
</h2>
<p size=large> Assignments of Data Mining course</p>
<div align="center">
</div>
<br>
</div>

## Preprocessing
This assignment includes handling of missing data, conversion of categorical values, data normalization, dimension reduction and data visualization.

## Classification
For this assignment we use data to try and reason the way our neural network model would perform classification with different hyperparameters. We compare the accuracy and loss of the model by changing activation and loss functions, layering and number of neurons. We find the optimum learning ratio and finally propose an accurate model.

## Clustering
For this assignment we use blobs as our data and <b>K-means</b> algorithm to cluster them and visualize the result. We further explore the performance and limitations of K-means by trying to determine the right value of K, for which we use elbow method. 
<br>
Then we use K-means for clustering digits and compare the performance of our model with or without dimension reduction and visualize the results.
<br>
Further we compress the image of a bird by performing K-means algorithm and clustering colors to 4 separate clusters and replacing each color with centroid of it's respective cluster.
<br>
We also use <b>DBSCAN</b> algorithm and find the best `eps` for it by performing KNN and `KneeLocator` where `K` is equal to `minPts` and compare the result with K-means by visualization.


## Association Rules
For this assignment we use `Hypermarket` dataset and <b>Apriori</b> algorithm to find all frequent itemsets and generate high confidence rules from each frequent itemset for specific support, confidence and lift.