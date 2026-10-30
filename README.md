# Down Syndrome Detection from Facial Images Using Deep Learning

## Overview

This project explores the use of deep learning techniques to analyze facial images and classify them into two categories: Down Syndrome and Non-Down Syndrome.

The project implements and compares three deep learning models: a custom Convolutional Neural Network (CNN), ResNet50, and VGG16. Their performance is evaluated using classification metrics to understand how different architectures perform on the image classification task.

This project was developed collaboratively as an academic minor project.

## Objectives

- Develop deep learning models for facial image classification.
- Implement a custom CNN and two pretrained architectures: ResNet50 and VGG16.
- Compare model performance using appropriate evaluation metrics.
- Explore the application of computer vision techniques to preliminary screening research.

## Models Implemented

### 1. Custom CNN
A Convolutional Neural Network designed to learn relevant features directly from facial images.

### 2. ResNet50
A pretrained deep learning architecture that uses residual connections to support the training of deeper neural networks.

### 3. VGG16
A pretrained convolutional neural network used for image classification through transfer learning.

## Technologies Used

- Python
- TensorFlow and Keras
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

```text
Down-Syndrome-Detection/
├── README.md
├── notebooks/
│   ├── cnn_down_syndrome_detection.ipynb
│   ├── resnet50_down_syndrome_detection.ipynb
│   └── vgg16_down_syndrome_detection.ipynb
├── requirements.txt
└── .gitignore
```

## Dataset

The project uses facial images for binary classification. The dataset must be obtained separately and configured according to the paths used by the notebooks.

The dataset is not included in this repository.

## Evaluation

The models are evaluated using classification metrics and visualizations generated during the experiments. The results can be examined in the respective notebooks.

## Contributors

This project was developed collaboratively by:

- Ekansh Gupta
- Mahima Singh Rathore
- Yugam Jain
- Aryan Verma
  
## Disclaimer

This project is intended for academic and research purposes only. It is an experimental machine learning project and is not a clinically validated diagnostic tool. Its predictions should not be used as a substitute for professional medical evaluation.
