Hii all,

## Unsupervised machine learning

<li>Unsupervised learning is a type of machine learning algorithm used to draw inferences from datasets consisting of input data without labeled responses. 
</li><li>The most common unsupervised learning method is cluster analysis, which is used for exploratory data analysis to find hidden patterns or grouping in data.</li>

## Clustering
**sklearn.cluster**
> Clustering can be defined as the task of identifying subgroups in the data such that data points in the same subgroup (cluster) are very similar while data points in different clusters are very different.
There are various methods of clustering among that KMeans is quie frequently used method.
<img src="https://miro.medium.com/max/875/1*HGxubBB0IKpNKW0Odo7lhw.gif" height="350" width="450">


## KMeans
>The KMeans algorithm clusters data by trying to separate samples in n groups of equal variance, minimizing a criterion known as the inertia or within-cluster sum-of-squares .
<img src="https://scikit-learn.org/stable/_images/sphx_glr_plot_kmeans_assumptions_0011.png" height="350" width="350">

## Elbow method
> elbow method is the most popular method which is used to determine the optimal value of K to perform the K-Means Clustering Algorithm.
<img src="https://media.geeksforgeeks.org/wp-content/uploads/elbow_3.jpeg" height="350" width="450">

The curve point which forms the elbow shape is the optimum KMeans value i.e K value
using the elbow method the k value can be founded out.
