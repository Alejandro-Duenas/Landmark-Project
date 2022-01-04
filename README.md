# Landmark Detection with PyTorch
***

## 1. Introduction
With the social media boom it is increasingly important to give a better
and more complete experice to the users. In particular, give a more
immersive experience to tourist that share their photos through social
media. This could be done through tags for the photos or additional 
information for tourist places, that could be facilitated through an
landmark recognition algorithm.

In this project I explore the creation of computer vision algorithms through
PyTorch to detect these landmarks. A sample of the landmark photos can be seen
below. 

![](images/sample.png)

There are 50 classes in the dataset used and around 5000 training images. To
tackle this complex problem I used:

+ Scratch convolutional neural network
+ Transfer learning with [DenseNet](https://pytorch.org/hub/pytorch_vision_densenet/)

## 2. Documentation
The main file used for this project is:

+ `landmark.ipynb`: Jupyter notebook that contains all the data prearations, 
model training, model testing and funtionality testging.

## 3. Tools and Software Used
+ JupyterLab: v.3.2.1
+ PyTorch: v.1.9.1
+ Numpy: v.1.19.2

## 4. License

This software is licensed under the [MIT](https://opensource.org/licenses/MIT) license.

## 5. Acknoledgements

This project was done as part of the [Udacity](udacity.com) Deep Learning Nano Degree

