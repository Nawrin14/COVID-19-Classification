# COVID-19-Classification

In this project, convolutional neural networks are trained for automatic detection of covid infection from the CT scan images. [[slides]](https://github.com/Nawrin14/COVID-19-Classification/blob/main/Presentation%20Slides.pdf)

# Dataset

The [SARS-COV-2 Ct-Scan Dataset](https://www.kaggle.com/datasets/plameneduardo/sarscov2-ctscan-dataset) has been used in this project.

# Pre-Trained CNN Models

1. ResNet50
2. Xception
3. DenseNet121
4. DenseNet201
5. MobileNet
6. MobileNetV2

# Steps

1. Data Preprocessing
2. Splitting Input Data
3. Image Augmentation
4. Applying Pre-Trained Models
5. Testing with Unknown Sample

# Performance Metrics

------------------------------------------------------------------------------------------
      Model      |     Accuracy     |     Precision     |     Recall     |     F1-Score
------------------------------------------------------------------------------------------
    ResNet50     |      95.97%      |       96.23%      |     94.44%     |      95.33%
    Xception     |      88.10%      |       80.08%      |     96.76%     |      87.63%
    DenseNet121  |      95.56%      |       93.69%      |     96.30%     |      94.98%
    DenseNet201  |      95.77%      |       94.12%      |     96.30%     |      95.20%
    MobileNet    |      93.15%      |       93.75%      |     90.28%     |      91.98%
    MobileNetV2  |      92.74%      |       91.28%      |     92.13%     |      91.70%
------------------------------------------------------------------------------------------


# Other Contributors

1. [Monjure Mowla Abir](https://github.com/abir2727) 
2. [Kaji Fuad Bin Akhter](https://github.com/FuadBinAkhter)
