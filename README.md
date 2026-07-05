# Image Classification

## Project Overview

This project develops an animal image classification model using Python and PyTorch.

The objective is to classify animal images into 151 categories using convolutional neural networks and transfer learning. The project compares a baseline CNN with pretrained deep learning models and evaluates model performance using accuracy and computational efficiency.

## Dataset

The project uses an animal image dataset containing:

- 151 animal categories
- 6,270 RGB images
- Image size: 224 × 224 pixels
- JPG image format

The dataset was split into training, validation and test sets.

## Methodology

The project follows these main steps:

1. Load and inspect image dataset
2. Apply image transformations and data augmentation
3. Split data into training, validation and test sets
4. Build a baseline convolutional neural network
5. Train and evaluate the baseline model
6. Apply transfer learning using pretrained models
7. Compare model accuracy, loss and FLOPs
8. Select the best model based on accuracy and efficiency

## Models Compared

The project compares several models:

- Baseline CNN
- ResNet18 transfer learning model
- VGG16 transfer learning model
- MobileNetV2 transfer learning model

MobileNetV2 was selected for further optimisation because it achieved strong accuracy with significantly lower computational cost compared with larger models.

## Results

The best selected model was based on MobileNetV2.

Final reported result:

- Model: MobileNetV2
- Learning rate: 0.001
- Epochs: 20
- Accuracy: 89.64%
- FLOPs: 0.16G
- Efficiency score: 560.22

The project demonstrates the trade-off between classification accuracy and model efficiency.

## Skills Demonstrated

- Python
- PyTorch
- Torchvision
- Computer vision
- Image preprocessing
- Data augmentation
- CNN model development
- Transfer learning
- Model training and validation
- Accuracy and loss evaluation
- FLOPs comparison
- Model selection

## Project Files

- `Image Classification.ipynb` – Main notebook containing data loading, model training, evaluation and comparison
