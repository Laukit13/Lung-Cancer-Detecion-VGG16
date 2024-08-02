# Lung Cancer Prediction Using VGG16

## Introduction

This project leverages the VGG16 deep learning architecture to predict lung cancer from medical imaging data. By using a pre-trained VGG16 model, fine-tuned on a specialized lung cancer dataset, we aim to achieve high accuracy and precision in detecting lung cancer.

## Model Architecture

We utilized the VGG16 model, pre-trained on the ImageNet dataset, as the backbone of our lung cancer classifier. This approach allows the model to capture intricate patterns and features relevant to lung cancer detection.

## Evaluation Metrics

The model's performance was evaluated on a validation set, yielding the following metrics:

- **Loss**: 7.1952
- **Accuracy**: 77.78%
- **AUC (Area Under the Curve)**: 0.8804
- **Precision**: 77.78%
- **Recall**: 77.78%

These metrics demonstrate the model's efficacy in distinguishing between cancerous and non-cancerous lung images, with substantial accuracy and precision in its predictions. The AUC score of 0.8804 reflects a high degree of separability between the classes, highlighting the model's potential utility in clinical settings for early and accurate lung cancer detection.

## Requirements

- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- VGG16

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/lung-cancer-prediction-vgg16.git
   cd lung-cancer-prediction-vgg16
