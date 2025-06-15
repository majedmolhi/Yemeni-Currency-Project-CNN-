# Yemeni Currency Classification Using CNN

This project aims to classify Yemeni banknotes into six categories using deep learning and Convolutional Neural Networks (CNN). We collected our own dataset, applied various augmentation techniques, and trained multiple pre-trained models such as MobileNet, DenseNet121, and EfficientNetV2.

## Dataset

The dataset contains **images of Yemeni currency (front and back sides)** collected manually and organized into six categories:
- 50 Rials
- 100 Rials
- 200 Rials
- 250 Rials
- 500 Rials
- 1000 Rials

## Model Architectures Used

We experimented with multiple pre-trained models:
-  MobileNet
-  DenseNet121
-  EfficientNetV2

The best result was achieved using **DenseNet121**, with an accuracy of **99.75%**.

## Data Augmentation

We applied the following augmentations:
- Rotation (±45°)
- Width & Height shift (0.2)
- Brightness (0.6 to 1.3)
- Zoom

This increased our training data from 1680 to over 10,000 images.

For dataset, trained models, and additional resources, check [Resources.txt](Resources.txt)
