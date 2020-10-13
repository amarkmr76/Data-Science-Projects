# Image captioning using VGG16, InceptionV3, ResNet50 and a Bidirectional LSTM

The objective of the project is to develop a model which takes as input an image and outputs a one line desscription of what's happening in the image.
The model is developed using the Flickr8k dataset*. The dataset consists of 8192 images and 5 captions associated with each image.
![alt text](https://github.com/[amarkmr76]/[Data-Science-Projects/Automated-Image-Captioning/]/blob/[master]/image.jpg?raw=true)

We leverage features extracted from VGG16, InceptionV3 and ResNet50 for images and a Bidirectional LSTM for the captions.
The repository conists of two notebooks: 1. EDA & Data preparation 2. Modeling & Evaluation.
The detailed modelling methodology and the reasoning behind is explained in the 2nd notebook.

* The reasoning behind going with Flickr8k instead of Flickr30k or MS-COCO is lack of computational power.
