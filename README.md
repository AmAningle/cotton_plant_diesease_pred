

# Cotton Plant Disease Prediction Using CNN

## Overview

This project focuses on predicting diseases in cotton plants using Convolutional Neural Networks (CNNs). The dataset contains images of cotton leaves categorized into four classes: diseased cotton leaf, diseased cotton plant, fresh cotton leaf, and fresh cotton plant. The project implements and compares various CNN architectures, including custom models and transfer learning approaches using ResNet50 and InceptionV3.

## Dataset

- **Training Data**: Contains images of ['diseased cotton leaf','diseased cotton plant','fresh cotton leaf','fresh cotton plant'] to classified into four categories.
- **Validation Data**: Used for tuning model hyperparameters and avoiding overfitting.
- **Test Data**: Used to evaluate the final model performance.

## Project Structure

1. **Data Preprocessing**:
   - Images are resized to 256x256 pixels.
   - Images are normalized to a scale of 0 to 1.
   - Data is split into training, validation, and test sets.

2. **Model Architectures**:
   - **Custom CNN**: Built from scratch using `Conv2D`, `MaxPooling2D`, `Dropout`, and `Dense` layers.
   - **ResNet50**: Utilizes transfer learning with ResNet50 pre-trained on ImageNet.
   - **InceptionV3**: Includes transfer learning with the InceptionV3 model.


## Results

### Custom CNN
- **Test Accuracy**: 88.89%

### ResNet50
- **Validation Accuracy**: 75.93%

### InceptionV3
- **Validation Accuracy**: 98.6%


## Requirements

- TensorFlow 
- Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib



