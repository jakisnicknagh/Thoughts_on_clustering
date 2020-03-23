# Thoughts_on_clustering - overview 

This repository contains final project for Data Science bootcamp. Main topic is presentation some methods for clustering mixed data, for this case Titanic dataset was used.

Clustering is a unsupervised method of machine learning, but could be used also in deep learning methodology. Mostly its helpful for data expolartion, and could be treated as prelimitary studies for classification.

This project was prepared as final project for Data Science bootcamp, will be presented some methods of clustering in .

# Goals

The goals was to build and compare some clustering methods:
  - K-Means clustering and MiniBatchKMeans
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


|    |   cluster_id |   unique_obs |   Survived |     Age |   Siblings/Spouses Aboard |   Parents/Children Aboard |     Fare |   Sex_female |   Sex_male |   Pclass_1 |   Pclass_2 |   Pclass_3 |
|---:|-------------:|-------------:|-----------:|--------:|--------------------------:|--------------------------:|---------:|-------------:|-----------:|-----------:|-----------:|-----------:|
|  0 |            0 |          296 |  -0        | 27.1419 |                  0.530405 |                  0.216216 |  12.2375 |            0 |          1 |         -0 |          0 |          1 |
|  1 |            1 |           94 |   0.968085 | 35.2553 |                  0.553191 |                  0.457447 | 106.126  |            1 |          0 |          1 |          0 |          0 |
|  2 |            2 |           77 |  -0        | 44.2922 |                  0.272727 |                  0.25974  |  62.8949 |           -0 |          1 |          1 |          0 |         -0 |
|  3 |            3 |           72 |  -0        | 23.4028 |                  1.29167  |                  1.09722  |  19.7731 |            1 |          0 |         -0 |          0 |          1 |
|  4 |            4 |           91 |   0        | 33      |                  0.307692 |                  0.142857 |  19.489  |           -0 |          1 |          0 |          1 |          0 |
|  5 |            5 |           72 |   1        | 20.8681 |                  0.5      |                  0.5      |  12.4645 |            1 |          0 |         -0 |          0 |          1 |
|  6 |            6 |           76 |   0.921053 | 28.9803 |                  0.486842 |                  0.605263 |  21.9701 |            1 |          0 |         -0 |          1 |         -0 |
|  7 |            7 |           45 |   1        | 36.7538 |                  0.377778 |                  0.311111 |  74.6373 |           -0 |          1 |          1 |         -0 |         -0 |
|  8 |            8 |           47 |   1        | 22.243  |                  0.340426 |                  0.297872 |  15.5797 |           -0 |          1 |         -0 |         -0 |          1 |
|  9 |            9 |           17 |   1        | 17.0782 |                  0.529412 |                  0.647059 |  21.0951 |           -0 |          1 |          0 |          1 |          0 |


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

![***Self Organising Map**](https://github.com/Fikus91/Thoughts_on_clustering/blob/master/4.%20Self%20Organising%20Map/Self%20Organising%20Map%2020.gif)


--in work--
