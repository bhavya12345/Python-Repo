The given file aims to build up a Neural Network from scratch which uses Sigmoid Function as the activation function.

The input variables and the output labels have been taken by myself on my own to illustrate the working of the Neural Network and the synaptic weights assigned to each of the layers. Initially, they are assigned random values between 0 and 1.

The NeuralNetwork class illustrates the essential methods for implementation of the Neural Network. It has been built using Numpy array in Python. The predict method is used for predicting the output label for a given set of inputs. The train method is being used for training the Neural Network on the data in which the synaptic weights of each of the layers are updated during each iteration using Gradient Descent and the error is calculated using the BackPropagation algorithm.

2 types of Neural Networks have been built here using 2 classes in a Jupyter Notebook:

1. A single layer neural network with 3 inputs and one output.

2. A 5 layer neural network with 3 inputs and one output.
 