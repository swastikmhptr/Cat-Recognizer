# Cat-Recognizer
Its a deep-learning model to recognize cat images using deeplearning Neural Networks

there has been no-wrappers used in the entire model and is made from scratch using numpy

There are 3 hidden layers in this neural network system:

The model id based on individual logistic regression neurons

1st layer:- Contains 4 neurons each having RELU activation
2nd Layer:- contains 6 neurons and each having TANH activation
3rd layer:- contains one neuron yielding the final output and having SIGMOID activation

The output from the sigmoid activated layer is then rounded to one integer values so as to yield the final result

OUTPUT:- 0=The image is not of a cat, 1=The given image is of a cat

Reault:- with the proposed 3 layer neural network an accuracy of >85% was obtained on the test dataset(without overfitting)
