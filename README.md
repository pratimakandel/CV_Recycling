# Computer Vision for Recycling

A deep convolutional neural network (CNN) is built in Python and trained on a labeled data set
of a thousand product images from various perspectives, to determine whether the object that is to be
recycled is composed of plastic, metal or glass. In order to provide the most efficient approach, I
experimented on well-known deep convolutional neural network architectures. By implementing
transfer learning and fine tuning to the pre-trained models with a common data augmentation strategy
ResNet101V2 model provided the best result with 82% test accuracy. A larger data set is required to
reduce overfitting and increase the accuracy.

The experiments of this research were executed using Keras library with TensorFlow back end
(version 2.3.0) on Google Colaboratory
