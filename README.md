# CustomerMall_segmentation_kmeans


CustomerMall segmentation based on kmeans algorithm.Kmeans is a unsupervised learning algorithm.

Basic requirements:

```javascript
Pandas
sklearn
matplotlib
```

To install above mentioned requirements first set-up pip installer for your python then run following commands in Command line:

```javascript
pip install pandas 
pip install sklearn
pip install matplotlib
```

Kmeans algorithm is a algorithm in which desired numbers of culsters created by taking mean of euclidean distance of centroids(clusters) and point we want to assign to that cluster.
 
Iterative process is taken to find a lowest mean in others words a centroids(clusters) choosen who give a lowest mean for all points surrounded them. Centroids are updated after every iteration.

Elbow method is used to find optimal number of clustors in a given data. In elbow method graph is based on a error/loss(total euclidean distance) vs Number of clusters. As number of clusters increase loss get decrease. Elbow method show us a cluster number from which decrease in a loss decrease rapidly so that is our elbow point.

Thanks and stay tuned.
