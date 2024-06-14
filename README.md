# Fully Connected Neural Network from scratch
This is the code for a fully connected neural network. It is written from scratch without using any ready-made deep learning library.  All the matrix operations are done using the numpy library. In this, classification is done on the MNIST dataset. We can give any number of hidden layers and any number of neurons in hidden layers as inputs. It is generalized to include various options for activation functions, loss functions, types of regularization, and output activation types. The following are the options available (text should be used as it is written below while giving the arguments for calling the functions):
Available Options (Type as given below while giving inputs as arguments):
1.	Hidden layer activation function: sigmoid, tanh, ReLu (default output activation is sigmoid)
2.	Output activation function: sigmoid (default), softmax (Boolean: True/False)
3.	Cost (Loss function): Quadratic, CrossEntropy
4.	Regularization: l1, l2
Above 97% classification accuracy can be achieved by using [784,100,10] architecture, CrossEntropy loss, l2 regularization, 30 epochs.

Although, MNIST dataset is used in the code, it can do classification for any dataset. Number of neurons in the input layer and the output layer has to be set as per the dataset.
