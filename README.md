## Skull Stripping and Classification of Autism Spectrum Disorder Using Deep Learning

### Overview
This project focuses on classifying Autism Spectrum Disorder (ASD) from brain MRI images using deep learning.
A Convolutional Neural Network (CNN) is used to distinguish ASD patients from normal controls after preprocessing MRI data.

### Problem Statement
Autism Spectrum Disorder is a neurological condition that affects behavior and social interaction.
Early and accurate diagnosis is important, but manual analysis of MRI images is complex and time-consuming.

### Dataset
The dataset is taken from the ABIDE-I (Autism Brain Imaging Data Exchange) database.
It contains MRI brain scans of ASD patients and normal controls.
A subset of 3D volumetric MRI images was used for this project.

### Preprocessing
Skull stripping (brain extraction)
Slicing 3D MRI volumes into 2D images
Histogram equalization
Normalization and rescaling of images to reduce computational complexity

### Model
A Convolutional Neural Network (CNN) is used for classification.
The architecture includes multiple convolution, pooling, normalization, and dropout layers followed by fully connected layers.
The model is trained using the Adam optimizer and binary cross-entropy loss.

### Training Details
Train-test split: 70% training, 30% testing
Batch size: 128
Number of epochs: 50

### Evaluation Metrics
Accuracy
Precision
Recall
Sensitivity
Specificity

### Results
The model achieved an average accuracy of approximately 75%.
High precision was observed, indicating effective differentiation between ASD and normal cases.
Training and validation loss decreased consistently over epochs.

### Conclusion
This project demonstrates that deep learning models can be used effectively for ASD classification from MRI images.
Proper preprocessing such as skull stripping and normalization plays a crucial role in improving performance.

Publication: https://ieeexplore.ieee.org/document/9984484
