# CSX_450_1_Project_2

# Plants Data

## Domain

This problem uses data from the USDA plant database including the scientific names and the location (states/territories) of all plants in the U.S.A. and Canada.

## Problem Statement

We will implement an unsupervised learning technique such as k-means to cluster the plants by location. This will project the 69 locations to 2 dimensions. From this we hope to be able to extract some information about the relation between these variables (plant families and locations). 


## Dataset

The USDA plants dataset (available [here](https://archive.ics.uci.edu/ml/machine-learning-databases/plants/))

- Number of samples: 34,781 
- Number of attributes: 70 (69 used)
- Expected Dataframe Dimensions: 34781 rows x 70 columns
- Column Data Types: All columns are a boolean if present in that state/country
- Target: n/a

** the plant name will be omitted from clustering as it is specific to each row and therefore would not contribute too clustering


## Solution Statement

A solution to this problem will be a cluster analysis using a model such as a KMeans Clustering or a Gaussian Mixture Model. 


## Benchmark Model

n/a 
or...
Coupled with climate zone maps, we could expect the plants in a cluster to map to similar zones.


## Performance/Evaluation Metric

Given that this is a clustering task, we can measure the success of our model using Silhouette Score
