# Food detection
This project implements a food detection model using a custom implementation of the ResNet-34 architecture. The model is trained to classify images into various food categories using the Foo-101 dataset.

## Overview
Food detection is a challenging task due to the wide variety of food types and appearances. This project addresses this challenge by implementing a custom version of the ResNet-34 architecture, a powerful convolutional neural network (CNN), which has shown excellent performance in image classification tasks. The Foo-101 dataset, consisting of images of 101 different food categories (I only used five classes for training due to the little computing power I have, but you feel free to use all classes and get better results), is used for training and evaluation.

## Features
* Implements a custom ResNet-34 architecture for accurate food detection.
* Provides tools for preprocessing images, training the model, and evaluating its performance.
* Addresses overfitting issues through regularization techniques such as dropout, data augmentation, or model architecture adjustments.

## Dataset
The Foo-101 dataset is a popular benchmark dataset for food classification tasks. It contains images of 101 different food categories, each with a varying number of samples. The dataset is split into training, validation, and testing sets to facilitate model training and evaluation.
* Dataset link: https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/

## Usage
To use this food detection model, follow these steps:
* **Data Preparation**: Download the Foo-101 dataset and organize it into appropriate directories (e.g., train, validation, test).
* **Preprocessing**: Optionally, preprocess the images (e.g., resizing, normalization) to prepare them for training.
* **Training**: Run the training script to train the model on the prepared dataset.
* **Evaluation**: Use the evaluation script to assess the model's performance on the test set.
* **Fine-tuning**: Experiment with different regularization techniques to address overfitting issues, such as dropout, data augmentation, or model architecture adjustments.

## Author
Alvaro Eduardo Torres Velasco
