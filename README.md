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
- 2 losses 
- Then optimizer
- Saving the checkpoints of your model

13) Defining the training loop

15) Update the parameters of both generator and discriminator so that they improve their performance
 tf.function
  - noise 
  - with tf.gradienttape 
  - generate_image with the noise we have above
  - Discriminator's Predictions
  - loss 
  - Gradient calculation
  - Updating the models and applying gradients. 

16) Training process for a GAN, updating the generator and discriminator with each batch of data across multiple epochs.

17) Generate and save images 

19) Train the model using the train above function with dataset and epochs

20) restore the checkpoint

21) Displaying a single image using epoch number and then display the image

22) Use imageio to create an animated gif using the images saved during training. And then display the gif 
