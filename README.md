# Optimization for machine learning : Mini-Project
## Description
This project was done in the framework of the course optimization for machine learning given at EPFL.
In this project, we compared the performance of several optimizers: SGD, \textsc{SGD with momentum}, \textsc{signSGD}, \textsc{signum}, \textsc{Adagrad} and \textsc{Adam}. We used them to train the ResNet-18 neural network on the MNIST dataset. We concluded that in this setup \textsc{SGD} is performing the best, reaching an accuracy of 95.04$\pm$0.54\%.\\
We then studied a decentralized learning approach where the parameters of the model are updated by grouping the outputs of different servers that work on separate data. We observed that this method is giving positive results when used with a simpler network than ResNet-18.

## Team members
* Camille Arruat
* Clément Jurat-Pentiadou
* Blerton Rashiti

## External libraries
We used the following libraries:
* [Pytorch](https://pytorch.org/)
* [Matplotlib](https://matplotlib.org/)
* [Numpy](https://numpy.org/)

## Python code

We have created several notebooks to realize this project:

