Mixture Density Networks in TensorFlow
=======
See ([Bishop, 1994](http://research.microsoft.com/en-us/um/people/cmbishop/downloads/Bishop-NCRG-94-004.ps)) for original paper

Description
-----------
An implementation of MDNs adapted from Andrej Karpathy's [example](https://github.com/karpathy/randomfun). My version is powered by [TensorFlow](https://www.tensorflow.org/versions/master/get_started/index.html)

Mixture Density Networks are just like vanilla neural networks but they return estimates of uncertainty on their predictions. Karpathy writes:

"The core idea is to have a Neural Net that predicts an entire (and possibly complex)
distribution. In this example we're predicting a mixture of gaussians distributions via
its sufficient statistics (the means and diagonal covariances), which are on the last
layer of the neural network. This means that the network knows what it doesn't know:
it will predict diffuse distributions in situations where the target variable is very
noisy, and it will predict a much more peaky distribution in nearly deterministic parts."

If you have any questions, contact me at sam.17@dartmouth.edu

Dependencies
--------
* All code is written in python 2.7. You will need:
 * Numpy
 * Matplotlib
 * [TensorFlow](https://www.tensorflow.org/versions/master/get_started/os_setup.html#pip_install)
