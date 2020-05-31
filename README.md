# Digit-Recogniser-with-MNIST-Data

Competition Website: https://www.kaggle.com/c/digit-recognizer/overview

The goal of Kaggle's Digit recogniser competition was to recognise digits from a set of handwritten digit images (MNIST Data). Built a CNN acheiving high accuracy and a high score (0.09971). 

CNN model architecture:  
*Conv2D-ReLU -> Conv2D-ReLU -> MaxPool2D -> Dropout -> Conv2D-ReLU -> Conv2D-ReLU -> MaxPool2D -> Dropout -> Flatten -> Dense -> Dropout*

Accuracy was improved by using an Annealer to decrease the learning rate so it correctly converges to the global minima as well as generating data by data augmentation to reduce overfitting.
