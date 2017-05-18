# K-Nearest Neighbors Algorithm

The K-Nearest Neighbors algorithm is a Machine Learning classification algorithm which takes into account the class label of the nearest values in order to make the classification. ‘K’ here denotes the number of nearest neighbors that needs to be considered in order to do the classification.

For any given point for which the class label needs to be predicted, the algorithm firstly calculates the Euclidean distance of that point from all the other points in the training dataset. Then after calculating the distances and storing them in an array or list, it takes the k minimum values of distances from that in order to know the points which are in the closest proximity of the test value. After taking the k points with minimum distances, it uses a voting approach in order to find out the class label of the test value. This implies that out of the k points with minimum distances, it checks that for which class label, the maximum points are present among those k points and assigns the same class label to the test value. This is how, the classification is accomplished for all the points using this algorithm.

The biggest advantage which is offered by the algorithm is that it is simple to understand and easy to implement as compared to the other Machine Learning Algorithms. Furthermore, KNN works just as easily with multiclass data sets whereas other algorithms are hardcoded for the binary setting.

The drawback of this algorithm is that it is computationally very expensive and prone to overfitting for large datasets.

For testing the implementation of this algorithm, the Iris dataset had been chosen and it was split into training and test samples. Their size was varied in order to check the accuracy given by the algorithm on varying size of training and test data. Also, the value of k was varied in order to know the accuracy for different number of neighbors for the given data. Since, the Iris dataset is a relatively simple and easier dataset with normalized values and less number of features, the accuracy obtained for the algorithm was quite high in almost all the cases and it also reached 100% sometimes. 
