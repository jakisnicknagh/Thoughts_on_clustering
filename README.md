# Thoughts_on_clustering - overview 
This repository contains final project for Data Science bootcamp. Main topic is presentation some methods for clustering mixed data, for this case Titanic dataset was used.

Clustering is a unsupervised method of machine learning, but could be used also in deep learning methodology. Mostly its helpful for data expolartion, and could be treated as prelimitary studies for classification.

This project was prepared as final project for Data Science bootcamp, will be presented some methods of clustering in .

# Goals

The goals was to build and compare some clustering methods:
  - K-Means clustering
  - Hierarchical clustering
  - Density based spatial clustering (DBSCAN)
  - Self Organising Map (deep learning method)


# Dependencies

  - Numpy
  - Pandas (03.2020 : for pandas-profiling == 0.25.3)
  - Matplotlib
  - pandas_profiling
  - sklearn
  - yellowbrick
  - scipy
  - minisom
  - pillow
  - glob
  
  
# Roadmap

 1. Data overview 
 2. Preprocessing
 3. K-means clustering
 4. Hierarchical clustering
 5. DBSCAN 
 6. Self Organising Map
 7. Summary

# Final results 

**K-Means**


|Name | Cluster 1	| Cluster 2 |
| ------------- | ------------- | ------------- |
|Survived|	0.19	| 0.74|
|Pclass|	2.39|	2.15|
|Age|	30.41|	27.77|
|Siblings/Spouses Aboard|	0.43|	0.69|
|Parents/Children Aboard|	0.24|	0.65|
|Fare	| 23.93|	47.44|
|Sex_female|	0.00|	0.99|
|Sex_male|	1.00|	0.01|
|unique_obs	|571|	316|


**Hierarchical clustering**

![**Hierarchical clustering**](https://github.com/Fikus91/Thoughts_on_clustering/blob/master/3.%20Hierarchical_clustering/hierarchy_titanic_normalized.png.png)


**DBSCAN**


|Name|   Cluster     -1    | Cluster     0    | Cluster     1    | Cluster    2    | Cluster     3    |
|:------------------------|-------:|-------:|-------:|------:|-------:|
| Survived                |   0.42 |   0    |   1    |  0    |   1    |
| Pclass                  |   2    |   2.48 |   1.92 |  2.89 |   2.03 |
| Age                     |  23.85 |  31.17 |  29.09 | 25.11 |  27.51 |
| Siblings/Spouses Aboard |   3.35 |   0.37 |   0.45 |  0.95 |   0.36 |
| Parents/Children Aboard |   2.08 |   0.16 |   0.46 |  0.97 |   0.34 |
| Fare                    | 174.39 |  19.62 |  46.52 | 17.81 |  32.01 |
| Sex_female              |   0.5  |   0    |   1    |  1    |   0    |
| Sex_male                |   0.5  |   1    |   0    |  0    |   1    |
| unique_obs              |  26    | 454    | 225    | 76    | 106    |




**Self Organising Map**


![Self Organising Map](https://github.com/Fikus91/Thoughts_on_clustering/blob/master/4.%20Self%20Organising%20Map/Self%20Organising%20Map%2020.gif)



--in work--
