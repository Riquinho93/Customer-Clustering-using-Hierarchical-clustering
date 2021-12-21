# Customer Clustering using Hierarchical clustering

![Dedrogram](https://github.com/Riquinho93/Customer-Clustering-using-Hierarchical-clustering/blob/main/dendrogram.png)

*Hierarchical grouping* - data is grouped in a tree and can be agglomerative and divisive, it depends on whether the hierarchical composition is
formed using a bottom-up (merge) or top-down (split) strategy.

I did a test with the agglomerative method which, with the bottom-up strategy, starts with allocation of each object in its own cluster. So, join these clusters
are carried out, forming increasingly larger clusters, until all objects be allocated in a single cluster or some stopping condition is satisfied.

## Approaches used in hierarchical algorithms

- Single linkage: each cluster is represented by all objects in it
contained, and the similarity between two clusters is represented by the distance between pairs
data/objects closer and belonging to different clusters.

- Complete linkage: uses the greatest distance between two groups. And the method
from the farthest neighbor. The distance between two clusters is determined according to
the greatest distance between a pair of data, with each data belonging to a cluster
distinct.

- Average linkage: uses the average between distances. That is, the
average of the distances between all pairs of data of two groups. pairs of groups
that have the lowest average are more similar.

- Affinity euclidean: how the distance between points is calculated.

## Tools used:

- Pandas (Data vizualization)
- Matplolib (Graphics and data vizualization)
- Scipy (Dendogram Visualization)
- Sklean (AgglomerativeClustering)

## Vizualizing the numbers of the clusters

![cluster](https://github.com/Riquinho93/Customer-Clustering-using-Hierarchical-clustering/blob/main/hierarchical%20clustering.png)
