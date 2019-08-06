# Traffic-Light-Classifier-
Implemented a classification pipeline that takes in an image of a traffic and outputs a label that classifies the image as a: red, yellow or a green traffic light.

The project was broken down into the following steps:
Loading and visualizing the data: The first step in any classification task is to be familiar with the data.

Pre-processing: The input images and output labels were standardized. This way, analysis of all the input images using the same classification pipeline was easily carried out, and I know what output to expect when eventually classifying a new image.

Feature extraction: Extracted a couple of features from each image that will help distinguish and eventually classify these images.

Classification and visualizing error: Wrote a function that uses the features to classify any traffic light image. This function will take in an image and output a label.

Evaluation: Classifier has an accuracy of 97.6% and it never classifies any red lights as green.
