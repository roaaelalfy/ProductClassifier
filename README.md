# Slash Product Image Classification 

This repository contains a comprehensive guide and code for training an image classification model using the MobileNetV2 architecture, fine-tuned for a custom dataset that contains local Egyptian brand products. My approach involves utilizing transfer learning and pre-trained models to achieve high accuracy with minimal training time and data. The code and its detailed explanation are found in the [image-classifier](https://github.com/roaaelalfy/ProductClassifier/blob/main/image-classifier.ipynb) file.

## Project Overview
We start by loading the MobileNetV2 model pre-trained on the ImageNet dataset, excluding its top classification layers to make it suitable for our custom classification task. This is followed by adding a custom classification head on top of the MobileNetV2 base, consisting of a Global Average Pooling 2D layer, a dense layer with ReLU activation for feature extraction, and a final dense layer with softmax activation tailored to the number of classes in our dataset.

## Key Features
1. MobileNetV2 trained on the ImageNet dataset
2. A classification layer on top of the MobileNetV2 base to tailor the model to our specific number of classes.
3. Data augmentation and normalization to improve model performance.
4. Detailed steps for model training, validation, and evaluation to ensure model effectiveness.
