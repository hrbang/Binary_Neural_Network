# Binary_Neural_Network

## Overview This is an implementation of a two-layer neural network during the live demo by @Sirajology on Youtube. The training method is stochastic (online) gradient descent with momentum. It computes XOR for the given input. It uses two activation functions, one for each layer. One is a tanh function and the other is the sigmoid function. It uses cross-entropy as it's loss function. This is all done in less than 100 lines of code. We're building this thing from scratch!

## What does it do?

##### Code view 1.

In this neural network i use the python library called "Numpy" I use this because it is my favorite library to work with when working with Mathematical Code

```
import numpy as np
import time
```

##### Code view 2.

This part of the code is where i get the output of what it have calculated for me

```
print "============================================"
print "XOR FORUDSEELSE:"
print ""
print x
print predict(x, *params)
print ""
print "============================================"
```

##### Code view 3.

This is the part where i define the Sigmoid function that i use in the Neural Network

```
def sigmoid(x):
    return 1.0/(1.0 + np.exp(-x))
```

## Usage

The way to use this Neural network is either to run it through python cmd or you can install [Anaconda](https://anaconda.org/anaconda/python) / [Miniconda](https://conda.io/miniconda.html)

and after simply just type this to make it run
```
python NN2.py
```
 Afterwards you can see it have run 100 different simulations which are called "Generations" because after each generation you can see it have been getting better in "Loss" section and that it because at every Generation we have trained it to be faster over time

 And then at last you can see it have spit out something that looks kinda like this
```
[0100101110]
[1011010001]
```
Now your neural network have converted all the zeros to ones and that is because we told it to take all the zeros place and replace it with a one and the other way around.


