# COVID-19-Classification

In this project, convolutional neural networks are trained for automatic detection of covid infection from the CT scan images.

# Dataset

The [SARS-COV-2 Ct-Scan Dataset](https://www.kaggle.com/datasets/plameneduardo/sarscov2-ctscan-dataset) has been used in this project.

# Pre-Trained CNN Models

1. MobileNet
2. MobileNetV2

# Steps

1. Data Preprocessing
2. Splitting Input Data
3. Image Augmentation
4. Applying Pre-Trained Models
5. Testing with unknown sample

# Performance Metrics

------------------------------------------------------------------------------------------
      Model      |     Accuracy     |     Precision     |     Recall     |     F1-Score
------------------------------------------------------------------------------------------
    MobileNet    |      93.15%      |       93.75%      |     90.28%     |      91.98%
    MobileNetV2  |      92.74%      |       91.28%      |     92.13%     |      91.70%
------------------------------------------------------------------------------------------
