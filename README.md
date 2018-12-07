# DenseNet-Keras
Implementation of DenseNet in Keras with Tensorflow backend

This is an ipython Notebook demonstrating the results of current DenseNet implementation. In Future, this will be extended to be imported as a python package.

Source:    Densely Connected Convolutional Networks https://arxiv.org/abs/1608.06993

Abstract:
Recent work has shown that convolutional networks can be substantially deeper, more accurate, and efficient to train if they contain shorter connections between layers close to the input and those close to the output. In this paper, we embrace this observation and introduce the Dense Convolutional Network (DenseNet), which connects each layer to every other layer in a feed-forward fashion. Whereas traditional convolutional networks with L layers have L connections - one between each layer and its subsequent layer - our network has L(L+1)/2 direct connections. For each layer, the feature-maps of all preceding layers are used as inputs, and its own feature-maps are used as inputs into all subsequent layers. DenseNets have several compelling advantages: they alleviate the vanishing-gradient problem, strengthen feature propagation, encourage feature reuse, and substantially reduce the number of parameters. We evaluate our proposed architecture on four highly competitive object recognition benchmark tasks (CIFAR-10, CIFAR-100, SVHN, and ImageNet). DenseNets obtain significant improvements over the state-of-the-art on most of them, whilst requiring less computation to achieve high performance.

Objectives:
1. To study the DenseNet Architecture and the Bottleneck-Compressed modification in it.
2. To deepen understanding of data augmentation and its regularizing impact.
3. To use Stochastic Gradient Descent as optimizer and experiment with various learning_rate/momentum strategies.

Results:
We achieve 91% accuracy as compared to Paper's 93% (without augmentation) and 94.7% (with augmentation) for CIFAR10 database.

