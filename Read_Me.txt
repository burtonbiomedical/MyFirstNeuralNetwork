--DLND My First Neural Network --

This constitutes the first project on my Deep Learning Foundation
Nanodegree from Udacity.

The notebook demonstrates a neural network that predicts the daily rental
ridership for a theoretical bicycle rental company.

Data preperation was provided by Udacity, and I was tasked with the creation
of a two layer neural network. The hidden layer uses a sigmoid activation
function, whereas the output node is used for regression and the output
is the same as the input for this node (i.e. the activation function is
f=f(x)).

I implemented the forward propagation of the network, and then used
backpropagation to propagate error backwards to update the weights
for each node.

Once the network was built and had passed the unit tests provided by
Udacity, I was tasked with chosing the correct number of iterations, the 
learning rate, and the number of hidden nodes, to successfully train
my network.

By evaluating the training and validation loss, I found the best
hyperparameters for my model without overfitting and with the best
generalisation.