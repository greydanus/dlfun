# TensorFlow Recurrent Mixture Density Network
----------
Tensorflow-powered model inspired by the 2014 Alex Graves handwriting [paper](http://arxiv.org/abs/1308.0850). Pieces of the code are taken from [hardmaru](https://github.com/hardmaru/write-rnn-tensorflow)

Description
-----------
The Alex Graves paper describes a deep neural network model with at least one recurrent cell (an LSTM in this case, though GRUs etc work too) and capped by a mixture density layer. At each time step the model predicts three values: an x value, a y value, and an end-of-stroke (eos) value. We use these predictions to draw patterns on a 2D canvas.

Alex Graves managed to mimic human handwriting, but this model is a lite version (I'm working towards that goal though). This model trains the network to draw a circle. The model is easily generalizeable, though, and can generally be used for training, saving, and running generation on scalable, n-dimensional recurrent models with 'confidence' estimates from the mixture density cap.

If you have any questions, contact me at sam.17(at)dartmouth.edu

Dependencies
--------
* All code is written in python 2.7. You will need:
 * Numpy
 * Matplotlib
 * [TensorFlow](https://www.tensorflow.org/versions/master/get_started/index.html)
