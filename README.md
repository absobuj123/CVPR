# PlantVillage CNN - Plant Disease Classification

## Project Overview
This project implements a custom Convolutional Neural Network (CNN) using PyTorch for multi-class plant disease classification.

## Dataset
- Dataset: PlantVillage
- Source: Hugging Face
- Total selected images: 8,000
- Number of classes: 20
- Image size: 64 × 64
- Training: 70%
- Validation: 15%
- Testing: 15%

## CNN Architecture
The custom CNN consists of:
- Two convolutional layers
- ReLU activation functions
- Max pooling layers
- Flatten layer
- Fully connected layers
- 20 output classes

## Training Configuration
- Optimizer: Adam
- Loss Function: CrossEntropyLoss
- Epochs: 20
- Batch Size: 32
- Learning Rate: 0.001

## Results
- Test Accuracy: 92%
- Correct Predictions: 1,104
- Incorrect Predictions: 96
- Total Test Images: 1,200

## Project Files
- `CNN_23_51821_2.ipynb`: Complete implementation and evaluation.
- `PlantVillage_CNN.pth`: Trained CNN model weights.


## Technologies Used
Python, PyTorch, Torchvision, NumPy, Matplotlib, Scikit-learn, Hugging Face Datasets, Google Colab.

## Author
Student ID: 23-51821
