# Project_cifar10
Classification of images in CIFAR10 dataset 
# Description
The CIFAR-10 data set has 10 classes: aeroplane, automobile, bird,cat, deer, dog,frog, horse, ship, truck. The data set has 60,000 images to classify. Training data set has 50,000 images and the testing dataset has 10,000 images. The original data set was divided into 5 training-batches and 1 test-batch having same number of images per class.
# Getting Started
# Dependencies
*Numpy
*Pandas
*Matplotlib
*Scikitlearn
*Pytorch
*Pickle
*Seaborn
# Contributors
*Hiteshi Singh (B19EE039)
*Zeba Karkhanawala (B19EE093)
*Kwanit Gupta (B19EE046)
# Steps
# Classifiers Used
*Neural Networks
Neural networks are a set of algorithms, modeled after the human brain, that are designed to recognize patterns. A neural network is composed of several layers which are made of nodes. A node combines input from the data with weights.These input-weight products are summed and then the sum is passed through a node’s activation function.
The neural network implemented using Pytorch consists of 3 hidden layers . The optimizer used is Adam . For hidden layers , ReLu function is used as an activation function . The best accuracy is obtained for 4 hidden layers which is 44.7
![nn](https://user-images.githubusercontent.com/66864077/118405623-76d5ba00-b696-11eb-8cba-4b5a540c1d33.png)
*K-Nearest Neighbor
In K-Nearest Neighbors, a data-point searches and find k nearest data-points, using Euclidean Distance, with their Sorted Indices according to the minimum Magnitude of Distances.
N_neighbors was pre-defined to be 20 in this scenario, but the effects were noticed using different Pre-Processing Techniques such as Standardization and Min-Maximization, alongside Dimensionality Reduction through Principal Component Analysis (at 90% data variance preservation).
![knn](https://user-images.githubusercontent.com/66864077/118405783-f6fc1f80-b696-11eb-94ab-cdab96483f38.png)
*K-Means Clustering
In K-Means clustering, the data set is partitioned into k pre-defined clusters. Each data point belongs to only one cluster. A data point is assigned to a cluster such that the sum of the squared distances between the data points and the cluster’s centroid is minimum.
For different values of k, the model was run, fitted onto the training dataset and then made a prediction. Values of k used  were 10,50,100,500,1000,3000 and 4000.  ![kmeans](https://user-images.githubusercontent.com/66864077/118405823-375b9d80-b697-11eb-99c3-2f27a166dbc3.png)
