# mnist_tutorial
A tutorial for MNIST handwritten digit classification using sklearn, PyTorch and Keras.

# Code structure
* [`numpy_matplotlib_sklearn.ipynb`](numpy_matplotlib_sklearn.ipynb): for numpy, matplotlib and sklearn.
* [`pytorch.ipynb`](pytorch.ipynb): for pytorch.
* [`keras.ipynb`](keras.ipynb): for keras.
* Reference solution: (not published yet)
    * [`numpy_matplotlib_sklearn_solution.ipynb`](numpy_matplotlib_sklearn_solution.ipynb)
    * [`pytorch_solution.ipynb`](pytorch_solution.ipynb)
    * [`keras_solution.ipynb`](keras_solution.ipynb)

# Requirements
Code tested on following environments, other version should also work:
* linux system (ubuntu 16.04) 
* python 3.6.3
* numpy 1.13.3
* matplotlib 2.1.0
* sklearn 0.19.1
* pytorch 0.4.1
* keras 2.1.2

# frame
* 网络采用两个卷积层和两个全连接层，激活函数采用relu，optimizer采用SGD，criterion采用CrossEntropyLoss

# accruacy
Q, train accruacy, test accruacy
* Q1, 97.50%, 89.70%
* Q2, 81.55%, 81.20%
* Q3, 97.83%, 86.80%
* Q4, 96.97%, 87.20%
* Q5, 98.91%, 98.09%

# For students from SJTU
Please read [HEAR](EE369.md).
