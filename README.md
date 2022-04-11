# Unsupervised learning & clustering
## Topic
Theoretical Assignment on clustering

1. 
    ##
    **Q:** What is clustering about ? 

    **A:** Clustering is the task of dividing the population or data points into a number of groups such that data points in the same groups are more similar to other data points in the same group than those in other groups. In simple words, the aim is to segregate groups with similar traits and assign them into clusters.

    ##
1. 
    ##
    **Q:** Give a few examples from real life where clustering should/could be used. 

    **A:** 
    1. Retail Marketing
    1. Streaming Services
    1. Sports Science
    1. Email Marketing
    1. Health Insurance
    ##
1. 
    ##
    **Q:** Name a few clustering algorithms besides K-Means

    **A:** 
    - Centroid-based Clustering.
    - Density-based Clustering.
    - Distribution-based Clustering.
    - Hierarchical Clustering
    ##

1. 
    ##
    **Q:** What is the idea behind the classic K-Means algorithms ? 

    **A:** The goal of k means is to group data points into distinct non-overlapping subgroups. You could elaborate on how it works. It is most effective when the clusters are spherical. There is a problem with the geometric shapes of clusters, which deviate from spherical shapes. Furthermore, it does not learn the number of clusters based on the data and must be predefined.
    ##
1. 
    ##
    **Q:** Is it important to scale? When and Why? 

    **A:** Scale is important simply because the magnitude of the problems faced in areas such as poverty reduction, the environment, gender issues and healthcare require solutions at scale.
    ##
1. 
    ##
    **Q:** Initialization of centroids is a problem in classic K-means. Why? What can one do instead of just one random selection of centroids? - number of random initializations - Position of centroids distant from each other's K-Means++ Explain! 


    **A:** Traditional k-means utilizes a randomization process for initializing these centroids -- though this is not the only approach -- but poor initialization can lead to increased numbers of required clustering iterations to reach convergence, a greater overall runtime, and a less-efficient algorithm overall.
    ##
1. 
    ##
    **Q:** What is inertia ?

    **A:** Inertia is the inherent property of a body that makes it oppose any force that would cause a change in its motion. A body at rest and a body in motion both oppose forces that might cause acceleration.
    ##
1. 
    ##
    **Q:** What is the idea behind MiniBatchKMeans? State the advantage and disadvantage behind using mini-batches. 

    **A:** The main advantage of a clustered solution is automatic recovery from failure, that is, recovery without user intervention. Disadvantages of clustering are complexity and inability to recover from database corruption. 

    ##
1. 
    ##
    **Q:** Optimal number of centroids can be be found by “elbow” techniques. How does it work? 

    **A:** The elbow method runs k-means clustering on the dataset for a range of values for k (say from 1-10) and then for each value of k computes an average score for all clusters. By default, the distortion score is computed, the sum of square distances from each point to its assigned center.
    ##
1. 
    ##
    **Q:**  Optimal number of centroids can be be found by “silhoutte” techniques. How does it work? 

    **A:** The silhouette method computes silhouette coefficients of each point that measure how much a point is similar to its own cluster compared to other clusters. by providing a succinct graphical representation of how well each object has been classified.
    ##
1. 
    ##
    **Q:** What is/are good alternative(s) to K-Means and when to use it? 


    **A:** Fuzzy c-means clustering can be considered a better algorithm compared to the k-Means algorithm. Unlike the k-Means algorithm where the data points exclusively belong to one cluster, in the case of the fuzzy c-means algorithm, the data point can belong to more than one cluster with a likelihood
    ##
