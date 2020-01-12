# Digit Recognizer with Pytorch
based on: https://www.kaggle.com/c/digit-recognizer
Project made to the introduction of the study of image recognition with deep learning using Pytorch.

## MNIST ("Modified National Institute of Standards and Technology")
MNIST datasets is one of the first things that you learn in computer vision. These datasets contains handwritten images that has served as the basis for benchmarking classification algorithms. This project uses a MNIST dataset of digits (0-9).

## Datasets
This project uses two datasets, both taken from kaggle. The 'train.csv' contains 42000 images each one with a label indicating the digit that the image represents, and it will be used to train a model that receive a image, and return the number that, based on its training, the model predicted. The 'test.csv' contains 28000 images but it doesn't have a label like the training dataset, the model created in this project that will fill the labels of the 'test.csv'.
The 'sample_submission.csv' is just a example provided by the kaggle showing how they want the format of the result.

## Convolutional neural network (CNN)
On this project was used a CNN, which is the main type of neural network for image recognition. This technique extracts the main features from images, making classification easier.

## Results
. Test accuracy: 0.99047

. Validation accuracy: 0.98984

. Subimission accuracy: 0.99042
