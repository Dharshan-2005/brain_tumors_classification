# Brain Tumor Classification with VGG16 and ResNet50

This repository contains a brain tumor classification model using deep learning. It uses pre-trained models like VGG16 and ResNet50 to classify brain tumors as either "Healthy" or "Tumor."

## Dataset

The dataset used for this project can be found at the following link:

[Kaggle Brain Tumor Dataset](https://www.kaggle.com/code/boneacrabonjac/brain-tumor-classification-with-simple-cnn)

- The dataset contains images of brain scans (both healthy and tumor).
- Please download the dataset and organize it into two folders: `Healthy` and `Brain Tumor`.

## Project Overview

1. **Data Preprocessing**: The dataset images are loaded and preprocessed using `ImageDataGenerator`. The images are rescaled and split into training and validation sets.
2. **Model Creation**:
   - **VGG16**: A model using the VGG16 architecture with pre-trained weights.
   - **ResNet50**: A model using the ResNet50 architecture with pre-trained weights.
3. **Ensemble Prediction**: Predictions from both models are combined using an ensemble approach to improve accuracy.

## Requirements

To run this project, you need to install the following dependencies:

- `tensorflow`
- `keras`
- `numpy`
- `matplotlib`
- `Pillow`

You can install the required libraries by running:

```bash
pip install tensorflow keras numpy matplotlib Pillow
