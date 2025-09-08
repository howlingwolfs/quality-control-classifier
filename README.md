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

### Two types of model trained

#### Own Keras (with/without augmentations)
#### Transferlearning Resnet50

### Image preparation:

<img width="682" height="495" alt="Capture" src="https://github.com/user-attachments/assets/ea32ec4f-2a78-48ff-b2c1-6839aa9e9783" />

<img width="370" height="260" alt="Capture 2" src="https://github.com/user-attachments/assets/b25325f4-2df1-4137-8941-3ce9a0b110df" />

<img width="658" height="424" alt="Capture 3" src="https://github.com/user-attachments/assets/bc0335d6-ec7c-4c27-a37c-0989323842b6" />

#### Accuracy on training set is 97%

#### Accuracy on test set is 86%

<img width="638" height="424" alt="Capture 4" src="https://github.com/user-attachments/assets/b77df439-c990-4bf1-8531-d00e434ad50f" />

### Augmentation

<img width="488" height="472" alt="Capture 5" src="https://github.com/user-attachments/assets/f835fc12-d230-4371-acf9-fc602e80468e" />

#### Accuracy on training set is 92%

#### Accuracy on test set is 83%

<img width="691" height="470" alt="download" src="https://github.com/user-attachments/assets/0601edf7-2a8a-4fcd-a474-c55a95702860" />

<img width="704" height="470" alt="download (1)" src="https://github.com/user-attachments/assets/9af32932-f30c-4bb4-b860-d6e19107bdfa" />

