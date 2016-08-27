# TensorFlow Adventures
----------
Tensorflow-powered machine learning experiments, usually in iPython

Description
-----------
A bunch of iPython notebooks I made while trying to teach myself machine learning/deep learning techniques. In order of quality:
* **[autoencoder](https://github.com/greydanus/adventures/tree/master/autoencoder)**
  * A simple autoencoder trained on the MNIST handwritten digit dataset
* **[mixture_density](https://github.com/greydanus/adventures/tree/master/mixture_density)**
  * Mixture Density Networks: they are just like vanilla neural networks but they capture uncertainty in their predictions using Gaussian kernels.
* **[graves](https://github.com/greydanus/adventures/tree/master/graves)**
  * Version 2.0 of _recurrent_mdn_
* **[recurrent_mdn](https://github.com/greydanus/adventures/tree/master/recurrent_mdn)**
  * Recurrent model with mixture density cap - a light version of the model described by [Alex Graves (2014)](http://arxiv.org/abs/1308.0850)

If you have any questions, contact me at sam.17(at)dartmouth.edu

All notebooks
-----------
* **[autoencoder](https://nbviewer.jupyter.org/github/greydanus/adventures/blob/master/autoencoder/mnist_autoencoder.ipynb)**: An autoencoder trained on the MNIST handwritten digit dataset
* **[mdn](https://nbviewer.jupyter.org/github/greydanus/adventures/blob/master/mixture_density/mdn.ipynb)**: Mixture density network implementation from Bishop's 1994 book, Machine Learning and Pattern Recognition
* **[train_shapes](https://nbviewer.jupyter.org/github/greydanus/adventures/blob/master/graves/train_shapes.ipynb)**: Implementation of the [2014 Graves paper](https://arxiv.org/abs/1308.0850) about handriting generation with RNNs but only does circle/square sequences right now
* **[generate_shapes](https://nbviewer.jupyter.org/github/greydanus/adventures/blob/master/graves/generate_shapes.ipynb)**: ^same
* **[circle_train](https://nbviewer.jupyter.org/github/greydanus/adventures/blob/master/recurrent_mdn/circle_train.ipynb)**: Recurrent neural network demo in TensorFlow for generating 2D coordinates 
* **[circle_generate](https://nbviewer.jupyter.org/github/greydanus/adventures/blob/master/recurrent_mdn/circle_generate.ipynb)**: ^same

Dependencies
--------
* All code is written in python 2.7. You will need (at the very least):
 * Numpy
 * Matplotlib
 * [TensorFlow](https://www.tensorflow.org/versions/master/get_started/index.html)
