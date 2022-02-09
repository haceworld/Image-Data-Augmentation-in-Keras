# Image-Data-Augmentation-in-Keras
Image data augmentation is a technique that can be used to artificially expand the size of a training dataset by creating modified versions of images in the dataset.
Training deep learning neural network models on more data can result in more skillful models, and the augmentation techniques can create variations of the images that can improve the ability of the fit models to generalize what they have learned to new images.

The Keras deep learning neural network library provides the capability to fit models using image data augmentation via the ImageDataGenerator class.
The Keras deep learning library provides the ability to use data augmentation automatically when training a model.

This is achieved by using the ImageDataGenerator class.

First, the class may be instantiated and the configuration for the types of data augmentation are specified by arguments to the class constructor.

A range of techniques are supported, as well as pixel scaling methods. Specifically, the five main types of data augmentation techniques for image data are; 

1.) Image shifts via the width_shift_range and height_shift_range arguments.
2.) Image flips via the horizontal_flip and vertical_flip arguments.
Image rotations via the rotation_range argument
Image brightness via the brightness_range argument.
Image zoom via the zoom_range argument.


Result of data augmentation
![results](https://user-images.githubusercontent.com/61402731/153237632-37c1fef3-f6d0-4302-a0db-0b9ad78fc119.PNG)
