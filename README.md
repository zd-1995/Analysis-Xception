# Analysis-Xception


On this page, the code in the link below is used, and we changed the pre-trained neural network type to Xception neural network. 
https://machinelearningmastery.com/how-to-visualize-filters-and-feature-maps-in-convolutional-neural-networks/

In this code, it is placed to extract the features of the images using the trained neural network. A bird image is examined for neural network and convolution filters and features extracted from convolution layers.

This code file with name AXcep.ipynb ,runs in colab and jupyter.

All parts of this file are as follows:

1) In part 1, Load Xception Pre-trained model and summaries that.

2) In part 2, In all layers of this model all of the cnn layers extract.

3) In part 3, Some convolution filters of the model are shown.

4) In part 4, The model is loaded and the bird image is sent to the network. The result of the image exit from the convolution layers, the number of 5x5 images that passed the convolution filters of the convolution layers is displayed.

* Results of images after applying convolution filters 

The image obtained by applying the convolution filter in the some layers:

- 1st layer: By changing the color space, try to separate the object from the background, which is distinguished by color.

- 2nd layer: It detects edges to improve the first image.

- 3rd layer: Extracts the features of the image with sharpness and smoothness.

- 4th layer: Adding noise to extract objects by means of texture analysis.

- 7th layer: Edge detection on the reduced image from the previous layers.

- 8th layer: The size of the image is reduced to extract the object range.

- 9th layer: Feature extraction to find the mask.

- 14th layer: Edge extraction from the image.

- 17th layer: Feature extraction for a part of the bird's body.

- 18th layer: Finding the object range.

- 19th layer: Expands the range of the found object.