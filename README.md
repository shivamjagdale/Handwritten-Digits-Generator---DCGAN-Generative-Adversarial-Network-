# Handwritten-Digits-Generator---DCGAN-Generative-Adversarial-Network-
Handwritten Digits Generator - DCGAN (Generative Adversarial Network) 

Here we are building Hand Written Digits Generator using Deep Convolutional Generative Advisor Network (DCGAN)
Here we are taking MNIST Handwrittedn images and this generator should generate the images that closely resemble real image. 

The main part is building 2 seperate neural networks where it takes random input, builds the image and other one is just a classification Neural Network that classifies images as fake or real. 

Here are some of the things we need to carry out :- 
1) Install the required liabries 
2) Import the required liabraries 
3) Get the dataset
4) Reshape the image and standardize the image
5) Define the sizes 
6) Batch and shuffle the data 
7) Setting the noise for random images so that we can pass them to our Generator
8) Generator Model
9) Pass random input to Generator model to generate an image, (This is an untrained generator model)
10) Discriminator model
11) Use untrained Discriminator to predict weather the image is real or fake. 
12) Loss and Optimiers :- 
- Crossentropy
