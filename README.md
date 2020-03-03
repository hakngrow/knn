K-nearest neighbors (kNN) is a supervised machine learning algorithm that can be used to solve both classification and regression tasks.  The algorithm works on the principle that data points that are close together, are similar.  The hyper-parameter, k, determines the number of 'nearest' data points to consider when predicting the outcome.  If k=5, the predicted class of a data point is derived via majority voting using the classes of the 5 nearest data points. In regression, the mean value of the 5 nearest points is used.
