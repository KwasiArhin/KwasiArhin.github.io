title: "Post: Standard"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - Post Formats
  - readability
  - standard





# NFL Cluster Analysis 

#### Introduction: 

The NFL has transitioned to a passing league over the last decade. More than ever before pass records are being broken. In this project I wanted to see if I make useful clusters using the Air Yards and Yards after catch statistics. 

#### In this project, I attempt to reach the following tangible goals:  
#### Data:

This dataset was scraped from the profootball reference with the aid of the Ryurko R wrapper.


#### Metrics:
Airyards: 

Yards after Catch: 



## Clustering of Pass-Catchers

We experimented with different clustering algorithms, but the best results were produced by K-Means Clustering and Spectral Clustering. K-Means was able to produce stable two-cluster and four-cluster solutions.

#### DBSCAN Solution:

![Cluster_means](README/table_clust.png)

The thematic differences between the clusters are rather intriguing. 

* For the first cluster,

* For the second cluster, "celebration of love and beauty" is important. However, the unique semantic component "weak man" is also very significant. "Farewell to love" is relevant.

* The third cluster seems to be comprised of starkingly "happy" and "light" poems. The only relevant semantic component is "celebration of love and beauty."

* The last cluster is a mix: "celebration of love and beauty" is more pertinent to this cluster than to any other clusters. However, the same is true of the semantic component of "fading." 

#### Conclusion::clipboard:

Analysis maybe utilized to assess an offensive scheme and how different players fit within it. 

