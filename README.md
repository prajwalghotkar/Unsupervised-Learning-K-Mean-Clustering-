# Unsupervised-Learning-K-Mean-Clustering

K Means Clustering 
WCSS- Within Cluster Sum of Squares  
![image](https://github.com/user-attachments/assets/2a722682-18ec-42b2-b5ad-d7a32bd32c65)

* X = Salary Y = spending Score (Create Clusters) 

* One centroid – Find WCSS from centroid using Euclidian distance 
  First centroid is in mean point

  ![image](https://github.com/user-attachments/assets/f3c55c06-308b-4e3f-abc9-9851cb5841cf)

* Once K =3 (Identified by Elbow method), system randomly generate three Centroids and three clusters, then centroid changes, 
  Repeat the process, still there are no further movements in the points / centroid  

* In K-means clustering, n_init is the number of times the algorithm runs independently. Each run uses different random centroids
   to choose the final model with the lowest within-cluster sum of squared errors (SSE). The default value for n_init is 10

* Check how many clusters to be created :

  init: {'k-means++', 'random' or an ndarray}
    Method for initialization, defaults to 'k-means++':

    'k-means++’: selects initial cluster centers for k-mean
    clustering in a smart way to speed up convergence. See section
    Notes in k_init for more details.

    'random': choose k observations (rows) at random from data for
    the initial centroids.

    If an ndarray is passed, it should be of shape (n_clusters, n_features)
    and gives the initial centers.

