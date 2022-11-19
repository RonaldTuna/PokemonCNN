# PokemonCNN

The CNN in this repository is modeled after the VGGNet configuration detailed in:
https://arxiv.org/pdf/1409.1556.pdf

A Pokemon identifying convolutional neural network written in Python on Google Collab, utilizing Keras to create, train and test the CNN on images saved on google drive. Skimage is used help augment the data, and matplotlib allows us to model the performance of our models. 

The data was collected from google images search results in the form of 300 images for each of the 151 pokemon. The images were then fit into a uniform 224x224 image as input for our neural network. Each image is then augmented using various skimage methods such as flipping or adding noise.

A validation accuracy of 17% was the highest achieved. This accuracy rate was thanks to configuration D2, which uses sigmoid as an activation function.

Overall, our I believe the data needs to be cleaner. There were images with some things that might have confused our CNN in the background, such as other pokemon, or trainers.
