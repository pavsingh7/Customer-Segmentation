# Customer-Segmentation

> Look to apply unsupervised learning techniques (clustering algorithms) to create customer segments. 


<img src="segments.jpg" width="570" height="350">



## Introduction

The goal of this project is to identify the customer segments hidden within a dataset of customer spending habits for a variety of products. The project involves using unsupervised learning techniques such as K-means clustering, PAM clustering, and Gaussian Mixture Model (GMM) clustering to group customers with similar spending habits into clusters.

## Data

The dataset for this project can be found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php). The data set refers to clients of a wholesale distributor. It includes the annual spending in monetary units (m.u.) on diverse product categories, for example, annual spending on fresh products, milk products, grocery products, frozen products, etc. More information can be found [here](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers).

## Clustering Algorithms

We apply the following clustering techniques to group customers into similar segments.


- **K-means Clustering**
  * K-means is a centroid-based clustering algorithm that partitions a dataset into k clusters, where k is a user-defined number of clusters. The algorithm uses the mean of the data points in each cluster to define the centroid of the cluster.

<br>

- **PAM Clustering**
  * PAM (Partitioning Around Medoids) is a variation of k-means clustering that uses medoids instead of centroids as the cluster representatives. A medoid is a data point that is the most centrally located within a cluster.

<br>

- **Gaussian Mixture Model (GMM) Clustering**
  * GMM is a probabilistic model that assumes that the data points in a dataset are generated from a mixture of several Gaussian distributions. The model parameters are estimated using the Expectation-Maximization (EM) algorithm.

## Results

TBD

## Conclusion

The customer segmentation project was a success in uncovering the hidden customer segments in the dataset. By using unsupervised learning techniques, we were able to group customers with similar spending habits into clusters, which can be useful for targeted marketing campaigns and personalized customer experiences.

***
## Getting Started

This project is implemented in Python. To run this project, the following software and packages are required:

- Python
- pandas
- numpy

To run this project, clone or download the repository and open the jupyter notebook. The code and data are included in the repository.

## Contributions

If you want to contribute to this project, feel free to submit a pull request or open an issue in the repository.

## Contact

For any questions or queries, please email: sngpav003@myuct.ac.za



