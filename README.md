# Optimization for machine learning : Mini-Project
## Description



## Reproduce our results


## Team members
* Camille Arruat
* Clément Jurat-Pentiadou
* Blerton Rashiti

## External libraries
We used the following libraries:
* [Pytorch](https://pytorch.org/)
* [Matplotlib](https://matplotlib.org/)

## Python code

We have created several python files that allow us to achieve our goal:

`Data.py`: This is the file which takes care of the data augmentation.

`Evaluation.py`: This file is used to evaluate the results obtained on the validation test by looking at various metrics.

`Metrics.py`: File containing useful functions for the simulation (loss function, iou ...) 

`Model.py`: File containing the u-net model structure.

`Train.py`: File dedicated to the training of the u-net model structure.

`Predict.py`: This is the file which takes care of doing predictions on the test set.

`All_in_one.py`: This is a file containing all the others as one. This is only to be run if there is a problem with the rest. This was the code that was used through out the project. The separation of files was done to emphasize a better project structure and facilitate partial code running.
