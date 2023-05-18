# Dog-Vision-playon-computer-vision

This is a Multi-Class Dog Breed Classification. 

This notebook builds an end-to-end multi-calls impage classifier using TensorFlow 2.12.x and FensorFlow Hub.

1. Problem
Identifying the breed of a dog given an image of a dog. When I'm sitting at the cafe and take a photo of a dog, I want to know what breed of dof it is.

2. Data
The data we're using is from Kaggle's dog breed identification completion

https://www.kaggle.com/c/dog-breed-identification/data

3. Evaluation
Submissions are evaluated on Multi Class Log Loss between teh predicted probability and the observed target. For each image in the test set, you must predict a probability for each of the different breeds. The file should contain a header and have a particular format.

Features
Some information about the data

We're dealing with images (unstructured data)so it's probably best we use deep learning/ transfer learning.
There are 120 breeds of dogs (this means there are 120 different classes).
There around 10,000+ images in the training set (these images have labels)
There around 10,000+ images in the test set (these images dont have labels, because we'll want to predict them).
