# Neural-Networks-and-Deep-Learning

Mini Projects that I've been creating while learning Neural Networks and Deep Learning through a textbook.

### Mini Projects Within This Repo:



### Digits:

This is a simple Python program that learns how to recognize handwritten digits, using stochastic gradient descent and the MNIST training data.

##### How to run this learning algorithm for yourself?

1. Open up a terminal and naivgate to the Digits folder.
2. Next, open a Python shell by typing the command "py" into your terminal.
3. Run the following scripts:

```
>>> import mnist_loader
>>> training_data, validation_data, test_data = \mnist_loader.load_data_wrapper()
>>> import network
>>> net = network.Network([784, 30, 10])
>>> net.SGD(training_data, 30, 10, 3.0, test_data=test_data)
```

After running all of these commands in succession, you should see the following appear in your terminal:

```
Epoch 0: 9129 / 10000
Epoch 1: 9295 / 10000
Epoch 2: 9348 / 10000
...
Epoch 27: 9528 / 10000
Epoch 28: 9542 / 10000
Epoch 29: 9534 / 10000
```

To understand more about what this code or these commands are doing, I highly reccomend checking out this section in Chapter One of [_Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/chap1.html#implementing_our_network_to_classify_digits)_.




