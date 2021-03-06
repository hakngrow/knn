#### K-nearest neighbors (kNN)

K-nearest neighbors (kNN) is a supervised machine learning algorithm that can be used to solve both classification and regression tasks.  The algorithm works on the principle that data points that are close together, are similar.  The hyper-parameter, k, determines the number of 'nearest' data points to consider when predicting the outcome.  If k=5, the predicted class of a data point is derived via majority voting using the classes of the 5 nearest data points. In regression, the mean value of the 5 nearest points is used.

Data points are determined to be close by meausring the distance between them. The [Euclidean distance](https://en.wikipedia.org/wiki/Euclidean_distance) is most commonly used as the distance metric to measure 'closeness'. 

Each feature of the dataset represents a dimension. A simple dataset with 2 features is represented by a 2-dimensional space with (x, y) co-ordinates.  This notebook will explain the K-nearest neighbors (kNN) algorithm using a synthetic dataset with 2 features. In real life problems, we typically have many samples with many features.
