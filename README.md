# Dogs Breed Identification

This repository contains the notebook I used to create a Dog Breed Identifier. The dataset I used was taken from a Dogs Breed Identification competition on Kaggle (https://www.kaggle.com/c/dog-breed-identification). The objective is to identify the breed of the dog presented in a given image, using a dataset that contains 120 dog breeds. I used the structure and tips from the Complete Machine Learning & Data Science Bootcamp 2023 course on Udemy (https://www.udemy.com/course/complete-machine-learning-and-data-science-zero-to-mastery/)

## Structure
The notebook starts with a short description of the problem.

It then proceeds to transform the more than 10000 images of dogs into tensors to be used for training and validation.

I took a Transfer Learning approach and imported a pre-trained Convolutional Neural Network (_mobilenet.v2_) on top of which I stacked a simple Dense Layer which would link the pre-trained features to dog breeds).

The performance is visualized at the end of the notebook using TensorBoard. The model confidence is also plotted for the top 10 predictions.

