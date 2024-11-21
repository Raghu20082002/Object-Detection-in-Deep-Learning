# Object Detection in Deep Learning: Comparative Analysis of YOLO, VGG16, ResNet50, and MobileNetV2

## Project Overview

This project performs a comparative analysis of various deep learning models for object detection, including **YOLO**, **VGG16**, **ResNet50**, and **MobileNetV2**. The models are evaluated using the **CIFAR-10** dataset, which consists of 60,000 32x32 color images across 10 object classes. The goal is to assess the performance of these models in classifying and detecting objects in the CIFAR-10 dataset.

## Models Implemented

- **YOLO-like Model**: A simplified version of YOLO for object detection using convolutional layers.
- **VGG16**: A deep convolutional neural network (CNN) with 16 layers, widely used for image classification tasks.
- **ResNet50**: A residual network with 50 layers designed to solve the vanishing gradient problem using skip connections.
- **MobileNetV2**: A lightweight CNN designed for mobile and embedded devices, optimized for speed and efficiency.

## Dataset

The **CIFAR-10** dataset is used in this project, consisting of 60,000 32x32 color images split into 10 classes:
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck


The dataset is divided into a training set of 50,000 images and a test set of 10,000 images.

You can download the CIFAR-10 dataset from Kaggle at the following link:

- **CIFAR-10 Dataset on Kaggle**: [https://www.kaggle.com/datasets/krishnaik06/cifar-10](https://www.kaggle.com/datasets/krishnaik06/cifar-10)

## Sample Output Images

### Test Image 1: [True Label] vs Predicted Labels

![Test Image 1](https://github.com/Raghu20082002/Object-Detection-in-Deep-Learning/blob/00ec48f7960ffb81f4c8071dadca07aaae8a585b/object1.png)
- **True Label**: [Cat]
- **VGG16 Prediction**: [Frog]
- **ResNet50 Prediction**: [Cat]
- **MobileNetV2 Prediction**: [cat]
- **YOLO-like Prediction**: [cat]

### Test Image 2: [True Label] vs Predicted Labels

![Test Image 2](https://github.com/Raghu20082002/Object-Detection-in-Deep-Learning/blob/00ec48f7960ffb81f4c8071dadca07aaae8a585b/object2.png)
- **True Label**: [Ship]
- **VGG16 Prediction**: [Frog]
- **ResNet50 Prediction**: [Automobile]
- **MobileNetV2 Prediction**: [Automobile]
- **YOLO-like Prediction**: [ship]
