# CSX_450_1_Project_2

Table of contents
=================
  
  * [Seeds](#seeds)
  * [Plants](#plants)


Seeds
=====

## Domain

This problem uses measurements of geometrical properties of kernels belonging to three different varieties of wheat. 

## Problem Statement

We will implement an unsupervised learning technique such as k-means to cluster the samples. This will project the 7 attributes to 2 dimensions. From this we hope to be able to extract some information about the relation between these variables and the type of wheat.


## Dataset

The seeds dataset (available [here](http://archive.ics.uci.edu/ml/datasets/seeds/))

- Number of samples: 210 
- Number of attributes: 7
- Expected Dataframe Dimensions: 210 rows x 7 columns
- Column Data Types: All columns are float
- Target: n/a

** An 8th column, the seed type (1,2 or 3), will be omitted from clustering since it is a label rather than an attribute.


## Solution Statement

A solution to this problem will be a cluster analysis using a model such as a KMeans Clustering or a Gaussian Mixture Model. 


## Benchmark Model

n/a


## Performance/Evaluation Metric

Given that this is a clustering task, we can measure the success of our model using Silhouette Score







# Plants

## Domain

This problem uses data from the USDA plant database (c.2008) including the scientific names and the location (states/territories) of all plants in the U.S.A. and Canada.

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
