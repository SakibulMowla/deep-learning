## Introduction to deep learning

### Sectors:
- healthcare
- agriculture
- self driving car
- etc.

### Neural Network:

Sample neural network in the following picture:

![neural-network](img/neural-network.JPG)

- leftmost layer is the input layer
- rightmost layer is the output layer
- layers in the middle are called hidden layers
- neural network itself is supposed to build the hidden layers

### Supervised Learning with Neural Networks

#### Standard Neural Network:
Real Estate, Online advertising

#### CNN:
Photo tagging

#### RNN:
Audio, Language

#### Custom/Hybrid Neural Network:
Autonomous Driving

![neural-network-types](img/neural-network-types.JPG)

### Structured Data

Well defined data. 
Ex: Size of bedroom, number of rooms in Real Estate example

### Unstructured Data

Not so well defined.
Ex: Audio, Image, Text.


### Why Deep Lwarning taking off

![neural-network-taking-off](img/neural-network-taking-off.JPG)

- NN (large one) works better than traditional algos when you have large amount of data
- Learning with RELU function doesn't slow down like sigmoid function
- short (and faster) feedback loop (idea -> code -> result) works better

### About the Course

![outline](img/outline.JPG)


## Neural Networks Basics

### Logistic regression

- it's an algorithm for binary classification (1 vs 0)

![logistic-regression](img/logistic-regression.JPG)


### Logistic regression cost function

- calculates the logistic regression parameter w anf b
- loss function computes the error for a single training example
- cost function is the average of the loss functions of the entire training set

![loss-function](img/loss-function.JPG)

### Gradient Descent

![gradient-descent](img/gradient-descent.JPG)

![gradient-descent-derivatives](img/gradient-descent-derivatives.JPG)


### Derivatives

- derivative is other name for **slope** (slope = height / width) 
- derivatives represent if you increase `a` by an infinitesimal (extremely small) amount, how much the function of a, `f(a)` will change. (Say f(a) = 3a)
- On a straight line, the function's derivative doesn't change
- but derivatives can be different for different point of a (different valiues of a). Example function, f(a) = a<sup>2</sup>

### Computation graph

- forward pass computes the output of neural network
- backward pass computes the gradients / derivatives

### Derivatives with a computation graph

![derivatives-backward](img/derivatives-backward.JPG)

### Logistic Regression Gradient Descent

![logistic-regression-derivatives-1](img/logistic-regression-derivatives-1.JPG)

![logistic-regression-derivatives-2](img/logistic-regression-derivatives-2.JPG)

![logistic-regression-gradient-descent](img/logistic-regression-gradient-descent.JPG)


### Vectorization

- art of getting rid of for loops

![logistic-regression-vectorization](img/logistic-regression-vectorization.JPG)

![logistic-regression-vectorization-2](img/logistic-regression-vectorization-2.JPG)

![logistic-regression-derivatives-3](img/logistic-regression-derivatives-3.JPG)

![logistic-regression-derivatives-4](img/logistic-regression-derivatives-4.JPG)

### Broadcasting in Python

![broadcasting](img/broadcasting.JPG)
