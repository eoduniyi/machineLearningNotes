# Convolutional Neural Network
**Convolutional Neural Networks** (CNN) *are a neural network architecture developed for computer vision tasks (i.e., regression and classification) that utilizes **kernel convolutions***. 

## Feature Extraction
![[CNN_Manual_FE.png]]

### Learning Feature Representations
![[CNN_Learning_FR.png]]

### Fully Connected Neural Network 
The input to this network is a 2D image represented as a column vector of pixels
![[AI/Machine Learning/Deep Learning/CNN/CNN_FCNN.png]]
![[CNN_FCNN_1.png]]

### Convolution Operation
The convolution operation is a mathematical operation that performs a **moving weighted average** (cumulative average or sum of elementwise multiplications between a filter ($f^{n \times n}$) and pixels of a 2D image ($x^{l \times l}$). The filter can be larger than the image, but in practice its size is a subset of the image's (e.g., $f^{4 \times 4} * x^{8 \times 8}$):

$$
\sum_{i=1}^4 \sum_{j=1}^4f_{ij}x_{ij}
$$

![[CNN_Spatial_Layers.png]]
![[CNN_Spatial_Structure.png]]
![[CNN_Convolution.png]]
![[CNN_Features_1.png]]
![[CNN_Features_2.png]]
![[CNN_Convolution_Operation_1.png]]
![[CNN_Convolution_Operation_2.png]]
![[CNN_Convolution.png]]

## Building CNNs
**Goal:** Learn features from image data and use said features to identify certain properties of images of a paticular type to inform some vision task. 

![[CNN_Classification.png]]

### Building Convolutional Layers
![[CNN_Convolution_Layer.png]]
![[CNN_Convolution_Spatial.png]]

### Non-Linearity
![[CNN_NL.png]]

### Pooling
A way to donsample and preserve spatial invariance
![[CNN_Pooling.png]]

## CNN Pipeline
![[AI/Machine Learning/Deep Learning/CNN/CNN_FL.png]]
![[AI/Machine Learning/Deep Learning/CNN/CNN_CP.png]]
![[CNN_Practice_1.png]]
![[CNN_Practice_2.png]]
![[CNN_Practice_3.png]]

## CNN Applications
![[CNN_Applications_1.png]]
![[CNN_Applications_2.png]]
![[CNN_Applications_3.png]]
![[CNN_Applications_4.png]]
![[CNN_Applications_5.png]]
![[CNN_Applications_6.png]]
![[CNN_Applications_7.png]]
