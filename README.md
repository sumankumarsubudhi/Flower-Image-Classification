# Flower-Image-Classification
This project is from Udacity machine learning nanodegree program which uses deep learning on Pytorch for classifying images of flowers

The image classifier is to recognize different species of flowers. Dataset contains 102 flower categories.

In Image Classifier Project.ipynb Alexnet from torchvision.models pretrained models was used. It was loaded as a pre-trained network, based on which defined a new, untrained feed-forward network as a classifier, using ReLU activations and dropout. Trained the classifier layers using backpropagation using the pre-trained network to get the features. The loss and accuracy on the validation set were tracked to determine the best hyperparameters.

