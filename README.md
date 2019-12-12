# Neural-Networks-on-Pulsar-Stars
The objective of this assignment is to implement a nonlinear regression and nonlinear logistic regression classifier by utilizing neural networks. The purpose of this is assignment is to explain and use 5-fold cross validation to find a good neural network parameters and report the CV accuracies.

First, the data is cleaned. Then, the data is visualized using heatmap, correlation, pairplot, countplot and grid.

Then the nonlinear regression is implemented using NeuralNet class. It consists of various defined functions like add_ones, pack, unpack, gradientf, optimtaregtf etc.

The nonlinear logistic regression is implemented using NeuralNetLog class. It consists of various defined functions like add_ones, pack, unpack, gradientf, optimtaregtf etc. Then this is implemented on toy dataset to see if the model is working or not.

A class for 5 fold cross validation is implemented using CrossValid class. Now, the result is checked by plotting the results.
