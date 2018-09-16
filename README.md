# Cat-Recognizer
This is a simple binary image classifier using a fully connected neural Network.

There are 3 hidden layers(3rd is the output layer) in this neural network system:

1st layer:- Contains 4 neurons each having RELU activation.

2nd Layer:- contains 6 neurons and each having TANH activation.

3rd layer:- contains one neuron yielding the final output and having SIGMOID activation

The output from the sigmoid activated layer is then rounded to one integer value(0 or1) so as to yield the final result

OUTPUT:- 0=The image is not of a cat, 1=The given image is of a cat

Result:- with the proposed 3 layer neural network an accuracy of >85% was obtained on the test dataset(without overfitting)
          , this result was obtained using only 200 images present in a .h5 format image dataset.
