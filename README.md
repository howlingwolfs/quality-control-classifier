# Image Classifier for Quality Control

Many factories need to detect whether a product is defective (cracks, scratches, wrong shape) or good.
We’ll train a CNN (Convolutional Neural Network) using Keras to classify images into Good vs. Defective.

Data set: 
[Kaggle](https://www.kaggle.com/datasets/ravirajsinh45/real-life-industrial-dataset-of-casting-product)

### Data Preparation
* Load dataset (train/valid/test split).
* Resize images (e.g., 128×128).
* Normalize (scale pixel values /255).
* Apply augmentations (rotation, flip, zoom).

