MNIST Autoencoder
=======
The basic idea behind an autoencoder is to teach a deep neural newtwork the identity function (ie reproduce its output). We make this hard for the network by forcing it to funnel the input data into a really low dimensional space, creating an information 'bottleneck' in the network. For example, here, our input space is a 28*28 dimensional vector which contains the information from one MNIST image. We then force the model to embed as much of the input data as possible into a 2 dimensional vector and recunstruct the input image using just that vector.

Autoencoders are cool because they force the network to save only the most important characteristics of the data, often revealing interesting patterns or insights about the data

![Samples from the MNIST autoencoder](../img/aec.png?raw=true "Title")

Dependencies
--------
* All code is written in python 2.7. You will need:
 * Numpy
 * Matplotlib
 * [TensorFlow](https://www.tensorflow.org/versions/master/get_started/os_setup.html#pip_install)
