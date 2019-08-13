# Flower-Image-Classification
This project is from Udacity machine learning nanodegree program which uses deep learning on Pytorch for classifying images of flowers

The image classifier is to recognize different species of flowers. Dataset contains 102 flower categories.

In Image Classifier Project.ipynb Alexnet from torchvision.models pretrained models was used. It was loaded as a pre-trained network, based on which defined a new, untrained feed-forward network as a classifier, using ReLU activations and dropout. Trained the classifier layers using backpropagation using the pre-trained network to get the features. The loss and accuracy on the validation set were tracked to determine the best hyperparameters.

### Command line applications train.py and predict.py
For command line applications there is an option to select either Alexnet or VGG13 models.

Following arguments mandatory or optional for train.py

1. 'data_dir'. 'Provide data directory. Mandatory argument', type = str
2. '--save_dir'. 'Provide saving directory. Optional argument', type = str
3. '--arch'. 'Vgg13 can be used if this argument specified, otherwise Alexnet will be used', type = str
4. '--lrn'. 'Learning rate, default value 0.001', type = float
5. '--hidden_units'. 'Hidden units in Classifier. Default value is 2048', type = int
6. '--epochs'. 'Number of epochs', type = int
7. '--GPU'. "Option to use GPU", type = str
