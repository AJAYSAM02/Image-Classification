# Image-Classification

In this project, we will build a convolution neural network in Keras with python on a CIFAR-10 dataset. First, we will explore our dataset, and then we will train our neural network using python and Keras.

## What is Image Classification?
The classification problem is to categorize all the pixels of a digital image into one of the defined classes.  
Image classification is the most critical use case in digital image analysis.  
Image classification is an application of both supervised classification and unsupervised classification.  
In supervised classification, we select samples for each target class. We train our neural network on these target class samples and then classify new samples.  
In unsupervised classification, we group the sample images into clusters of images having similar properties. Then, we classify each cluster into our intended classes.  

## About the Dataset Used
CIFAR-10 is a very popular computer vision dataset. This dataset is well studied in many types of deep learning research for object recognition.  
This dataset consists of 60,000 images divided into 10 target classes, with each category containing 6000 images of shape 32*32. This dataset contains images of low resolution (32*32), which allows researchers to try new algorithms.  
Also, CIFAR-10 dataset is already available in the datasets module of Keras. We do not need to download it; we can directly import it from keras.datasets.

