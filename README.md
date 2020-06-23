# Neural-Network-Assignments
### Problem Statement
In this assignment, you will build a complete neural network using Numpy. You will implement all the steps required to build a network - feedforward, loss computation, backpropagation, weight updates etc.

#### The assignment is divided into the following sections:
  Data preparation
  Feedforward
  Loss computation
  Backpropagation
  Parameter updates
  Model training and predictions
  
#### Data Preparation
You do not have to write any code in this section (Data Preparation). Please refer to the code provided in the notebook while going through these sections.
Firstly, we load the data using the function load_data(). The function data_wrapper() is then applied to the data to get the train and test data in the desired shape. Please note that the code needs to take a batch of data points as the input. Hence, be careful while checking the dimensions.
You already know that we have 28x28 greyscale images in the MNIST dataset. Hence, each input image is a vector of length 784. The ground truth labels of a batch are stored in a matrix which is converted to a one-hot matrix. Also, the output of the model is a softmax output of length 10. 
