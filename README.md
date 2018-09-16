# Convolutional Neural Network 
On the process of learning Deeplearning, i built Basic Convolutional Nural Network to get full understanding without help of ML library.

## Overview
A Convolutional Neural Network written in Python, consisting of a single neuron that uses back propagation to learn.
Just three layers are created which are convolution (conv for short), ReLU, and max pooling. The major steps involved are as follows:

1. Reading the input image.
2. Preparing filters.
3. Conv layer: Convolving each filter with the input image.
4. ReLU layer: Applying ReLU activation function on the feature maps (output of conv layer).
5. Max Pooling layer: Applying the pooling operation on the output of ReLU layer.
6. Stacking conv, ReLU, and max pooling layers.

You can have quick review with [juputer notebook file](https://github.com/avvineed/Convolutional-neural-network-Numpy/blob/master/CNN.ipynb).

## Dependencies

* numpy.
* skimage.data (Just to Fetch image Data)
* matplotlib (For Displaying Output)

## Credits
-  [Ahmed Gad](https://github.com/ahmedfgad/) [blog](https://www.kdnuggets.com/2018/04/building-convolutional-neural-network-numpy-scratch.html).
- [Andrew Ng](https://www.coursera.org/lecture/convolutional-neural-networks/)
- [Siraj Raval](https://github.com/llSourcell) for his [video](https://www.youtube.com/watch?v=FTr3n7uBIuE&t=1782s)
