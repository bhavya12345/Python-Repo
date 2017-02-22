The given file aims to implement the PCA or Principal Component Analysis algorithm from scratch. PCA is a dimensionality reduction algorithm which is used to convert a dataset of given dimensions into a dataset of lower dimensions.

The dimensionality reduction is being performed for a given dataset for the following:

1.Space efficiency

2.Computing efficiency

3.Data Visualization (reducing it to 2 or 3 dimensions so that it can be visualized by the human eye)

In the given project, a random 3-dimensional dataset of numbers has been generated and it has been reduced to 2-dimensions using the PCA algorithm. Firstly, the covariance matrix for the data has been computed which models the relationship between different features. It is followed by finding the eigen values and eigen vectors of the covariance matrix. 
It is followed by forming the eigen pairs consisting of both the eigen values and the eigen vectors. These eigen pairs are arranged in descending order and the first 2 eigen pairs are chosen which forms a 2 x 3 matrix. This matrix is multiplied with the dataset's transpose (which is 3 x 40) in order to obtain a dimensionality reduced dataset which has got 2 features and 40 instances.

In the end, the dataset has been represented on a graph using Matplotlib. Further work can be done to compare PCA with more dimensionality reduction algorithms like LDA and T-SNE. 