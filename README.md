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

## Feature Extraction and Fine Tuned Experiment 

![alt text](https://github.com/pratimakandel/CV_Recycling/blob/master/chart.png/?raw=true)

The dataset used to train the model is from the TrashNet dataset [1]. The images on this dataset consist of photographs of garbage taken on a white
background. More datasets of household items were collected from  Google Open Images Dataset V6 and google images. Each image was resized down to 150 x 150 pixels.

References:

1. Thung, Gary and Mingxiang, Yang. “Classification of Trash for Recyclability Status.” 2016.
http://cs229.stanford.edu/proj2016/report/ThungYang-ClassificationOfTrashForRecyclabilityStatus-report.pdf​ .
Accessed 16 November 2020

## Demo

![alt text](https://github.com/pratimakandel/CV_Recycling/blob/master/Result.PNG?raw=true)
