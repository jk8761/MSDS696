# MSDS696

# NOT DONE YET - Will include full links and video soon

## Project Abstract

Refs(1) : The MNIST Database: http://yann.lecun.com/exdb/mnist/

Abstract: Pres - ProjectAbstract.doc
* viewed here: https://github.com/jk8761/MSDS696/blob/master/Pres%20-%20ProjectAbstract.doc
* summary presentation: https://github.com/jk8761/MSDS696/blob/master/Abstract%20Object%20Image%20Recognition.pptx

This project will accomplish Image recognition on the MNIST dataset of handwritten digits, available from ref(1). The dataset is separated into a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. The digits have been size-normalized and centered in a fixed-size image

## Data Preparation and Discovery
Exploratory Data Analysis: Pres - ProjectImportEDA.doc
* viewed here: https://github.com/jk8761/MSDS696/blob/master/Pres%20-%20ProjectImportEDA.doc
* summary presentation: https://github.com/jk8761/MSDS696/blob/master/MNIST%20Dataset%20Object%20Image%20Recognition.pptx

The purpose is to use the NIST dataset and process those images using toolsets Python (on jupyter) and TensorFlow/Keras.

Data Discovery will be to visualize and verify the MNIST dataset. Data Cleansing steps normally used to prepare the dataset will also be included as necessary; these steps are to standardize, impute, dimensional reductions, etc. It is assumed that the dataset will not need Data Cleansing other than verifying the formats.

## Neural Network
Neural Network Analysis: Pres - ProjectCNN.doc
* viewed here: https://github.com/jk8761/MSDS696/blob/master/Pres%20-%20ProjectCNN.doc
* summary presentation: https://github.com/jk8761/MSDS696/blob/master/CNN%20Object%20Image%20Recognition.pptx

Summary: 
A Simple Neural Network (NN) and Convolutional Neural Network (CNN) will be used to accomplish Image Recognition. NN is used as benchmark comparison for the CNN (educational purposes); the analysis will be accomplished using a simple NN and compared to the CNN on the very same dataset

Convolutional Neural Networks
Convolutional Neural Networks (CNNs) are the current state-of-the-art model architecture for image classification tasks. CNNs apply a series of filters to the raw pixel data of an image to extract and learn higher-level features, which the model can then use for classification. CNNs typically contain three components:

•	Convolutional layers, which apply a specified number of convolution filters to the image. For each subregion, the layer performs a set of mathematical operations to produce a single value in the output feature map. Convolutional layers then typically apply a ReLU activation function to the output to introduce nonlinearities into the model.

•	Pooling layers, which downsample [dimensionally reduce] the image data extracted by the convolutional layers to reduce the dimensionality of the feature map in order to decrease processing time. A commonly used pooling algorithm is max pooling, which extracts subregions of the feature map (e.g., 2x2-pixel tiles), keeps their maximum value, and discards all other values.

•	Dense (fully connected) layers, which perform classification on the features extracted by the convolutional layers and downsampled by the pooling layers. In a dense layer, every node in the layer is connected to every node in the preceding layer.

The final dense layer (typically called "fully connected") in a CNN contains a single node for each target class in the model (e.g. all the possible classes the model may predict), with a softmax activation function to generate a value between 0–1 for each node (the sum of all these softmax values is equal to 1). Interpret the softmax values for a given image as 'relative measurements' of how likely it is that the image falls into each target class.

## Condensed Summary
The Results from the Simple Neural Network and Convolutional Neural Network comparison can be found here:
https://github.com/jk8761/MSDS696/blob/master/Results%20Object%20Image%20Recognition.pptx

Overall Full Video Summary Presentation: https://www.youtube.com/
