# Waste Classification Project

This project focuses on classifying waste images into two categories: Organic (O) and Recyclable (R) using deep learning models.

## Overview

- The dataset is sourced from the Kaggle Waste Classification Dataset and contains labeled images for training and testing.
- Pre-trained models like EfficientNetB0, ResNet50, and MobileNetV2 are used for transfer learning and fine-tuning to improve classification performance.

## Workflow

1. **Dataset Preparation**:
   - The dataset includes separate directories for training and testing images.
   - Data augmentation techniques are applied to enhance generalization.

2. **Preprocessing**:
   - Images are resized and normalized to ensure compatibility with the models.
   - Data augmentation involves rotation, zooming, and flipping to diversify training samples.

3. **Model Training**:
   - Pre-trained models are fine-tuned for binary classification.
   - Custom layers are added to adapt the models to the specific task.

4. **Evaluation**:
   - Models are evaluated on a test set for accuracy and loss.
   - MobileNetV2 achieved the best accuracy of 88.97%.

5. **Visualization**:
   - Training and validation metrics are plotted to analyze model performance.
   - Sample predictions are displayed to validate results.

## Key Results

- **Best Model**: MobileNetV2
- **Test Accuracy**: 88.97%
- **Applications**: This classification system can help in automated waste sorting systems, reducing manual effort and improving recycling efficiency.

## How to Use

1. Prepare the dataset by downloading it from Kaggle.
2. Train the models using the labeled dataset.
3. Evaluate and visualize the results to identify the best-performing model.
4. Deploy the chosen model for real-world waste classification tasks.

## Conclusion

This project demonstrates the use of transfer learning for a practical classification problem. By leveraging pre-trained models and data augmentation techniques, it achieves high accuracy and showcases the potential for real-world applications.
