
# Diabetic Retinopathy Detection (Blindness Detection)

This project is part of my internship at CodeClause and focuses on using machine learning techniques, specifically Convolutional Neural Networks (CNN), for the detection of diabetic retinopathy, commonly known as blindness. The model is trained to analyze retinal images and identify signs of diabetic retinopathy, which is crucial for early diagnosis and intervention.

## Overview

- **Convolutional Neural Network (CNN):** The project utilizes a CNN architecture for image classification, achieving an accuracy of approximately 98%.
- **Image Data:** The model is trained on a dataset of around 3700 retinal images, with five different classes representing varying degrees of diabetic retinopathy.
- **Image Augmentation:** To enhance the model's robustness, image augmentation techniques such as zooming, shifting, and scaling are applied during the training process.
- **Transfer Learning:** Fine-tuning is performed using transfer learning with a pre-trained model to boost performance on a relatively small dataset.
- **GitHub Actions:** Continuous Integration (CI) is set up using GitHub Actions to automatically run tests and ensure the project's stability.

## How to Use

1. **Dataset:** You can find the dataset used for training [here](https://www.kaggle.com/code/akshat0007/diabetic-retinopathy-detection-and-classification/notebook#Diabetic-Retinopathy).
2. **Training:** The model training script is available in the `Blindness_Detection.ipynb` directory. Adjust the hyperparameters as needed.
3. **Inference:** Once trained, the model can be used for inference on new images. 

## Requirements

- Python 3.x
- TensorFlow
- keras
- tkinter
- sklearn

## Acknowledgments

Special thanks to CodeClause for providing the internship opportunity.
