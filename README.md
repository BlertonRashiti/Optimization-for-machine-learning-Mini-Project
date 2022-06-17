# Optimization for machine learning : Mini-Project
### Study of different optimizers for a non-convex classification problem and comparison with a distributed method of optimization
## Description
This project was done in the framework of the course optimization for machine learning given at EPFL.

In this project, we compared the performance of several optimizers: SGD, SGD with momentum, signSGD, Signum, Adagrad and Adam. We used them to train the ResNet-18 neural network on the MNIST dataset. We concluded that in this setup SGD is performing the best, reaching an accuracy of 95.04%.

We then studied a decentralized learning approach where the parameters of the model are updated by grouping the outputs of different servers that work on separate data. We observed that this method is giving positive results when used with a simpler network than ResNet-18.

## Team members
* Camille Arruat
* Clément Jurat-Pentiadou
* Blerton Rashiti

## External libraries (Requirements)
We used the following libraries:
* [Pytorch](https://pytorch.org/)
* [Matplotlib](https://matplotlib.org/)
* [Numpy](https://numpy.org/)

## Python code (Reproducibility)

The main notebook is :
* notebook.ipynb

We have created several notebooks to realize this project:
* Tune_hyperparameters_SGD.ipynb
* grid_search_sign(um)SGD.ipynb : Searching the best hyper-parameters for SignSGD et Signum
* notebook_adagrad.ipynb
* notebook_adam.ipynb
* comparison_workers.ipynb : Comparison between different neural nets and optimizers for a server-based implementation
* Test - Error Feedback SignSGD.ipynb : Test of another server-based implementation, with error-feedback
