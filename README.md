# Clustering With Categorical Data

## UNDER-CONSTRUCTION

## Background

Clustering allows a data analyst or scientist to group or bin different populations for analysis based on their characteritics. For example, one could use binning for classifying music into music genres or customers into distinct customer segments.

Popular algorithms, like kmeans, require continious variables. One issue is that real-world data often contains copious amounts of categorical data. 

To overcome this problem, we can turn to examples like that put forth from [Jorge Lasaosa's medium article](https://towardsdatascience.com/clustering-on-numerical-and-categorical-features-6e0ebcf1cbad) on using a Gower dissimalairty matrix. It is important to note that any unsupervisied algorithm must not rely on euclidean geometry/distance assumptions (like kmeans). 

## The Dataset

The [Center for Machine Learning and Intelligent Systems](https://archive.ics.uci.edu/ml/index.php) at the University of California, Irvine maintains a large repository of open datasets that can be used for machine learning problems. 

For this analysis, the [South German Credit (UPDATE) Data Set](https://archive.ics.uci.edu/ml/datasets/South+German+Credit+%28UPDATE%29#) will be utilized.

## Clustering Approach


