# Red Blood Cell Classification using Convolutional Networks
## Exploring Machine Learning Applications in Pathology

This project investigates the application of machine learning techniques to problems in pathology. Using a dataset compiled by pathologists at the Yale School of Medicine, I develop a model to classify red blood cells into different groups of pathological significance. A number of convolutional network architectures are explored and tested on the original dataset of 750 images. Using a deep convolutional neural network, I am able to achieve up to 97% accuracy, a significant improvement over previous approaches.

Historically, approaches to histopathological image analysis in digital pathology have focused primarily on low level image analysis tasks (e.g., color normalization, nuclear segmentation, and feature extraction), followed by construction of classification models using classical machine learning methods, including: regression, support vector machines, and random forests.

Since 2012, deep learning-based approaches have consistently shown best-in- class performance in major computer vision competitions, such as the ImageNet challenge. This project was an attempt to apply a deep convolutional network to a classification problem in pathology. In a deep learning based approach there is no need for manual feature extraction. Instead, the deep learning algorithms take as input only the images and their labels and learn a complex set of model parameters with supervision coming only from the image labels, building on internal representations of the image.

The model trained on a dataset collected by Dr. Torres’ pathology lab is able to achieve a high classification accuracy of 97.59%, even with limited training data. Since the errors made by the model are concentrated in the classes with very few samples to train on, it is likely that the architecture has the potential to attain even better results with better training data. This is a promising result, since the convolution network is able to outperform traditional approaches in digital pathology and has the potential to be a useful aid in the daily practice of a pathologist.
