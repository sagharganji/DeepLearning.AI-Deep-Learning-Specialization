# Course 4: Convolutional Neural Networks

This repository contains all programming assignments, quizzes, and resources from Course 4 of the DeepLearning.AI Deep Learning Specialization on Coursera, taught by Andrew Ng.

## Overview

In this course, you will learn how to build convolutional neural networks (CNNs) and apply them to image data. The course explores core components of CNNs, modern architectures such as ResNet and YOLO, and advanced applications like face recognition and neural style transfer.

Key topics include:

- Convolutional and pooling operations
- Deep convolutional architectures (ResNet, MobileNet)
- Object detection (YOLO)
- Image segmentation (U-Net)
- Face recognition using triplet loss
- Neural style transfer

## Course Structure

### Week 1: Foundations of Convolutional Neural Networks

**Topics:**
- Convolutional layers, padding, and stride
- Pooling layers
- Basic CNN architecture
- Implementation of CNNs from scratch

**Assignments:**
- `Convolution Model Application`
- `Convolutional Model, Step by Step`

**Quiz:**
- `Week 1 Quiz - The Basics of ConvNets.pdf`

---

### Week 2: Deep Convolutional Models: Case Studies

**Topics:**
- ResNet architecture
- Identity and convolutional blocks
- Transfer learning with MobileNet
- Real-world use cases of deep CNNs

**Assignments:**
- `Residual Networks`
- `Transfer_learning_with_MobileNet_v1`

**Quiz:**
- `Week 2 Quiz - Deep convolutional models.pdf`

---

### Week 3: Object Detection and Segmentation

**Topics:**
- Object detection using YOLO
- Anchor boxes and non-max suppression
- Semantic segmentation with U-Net

**Assignments:**
- `Car Detection with YOLO`
- `Image Segmentation with U-Net`

**Data Folders:**
- `CameraRGB/` – Original input images
- `CameraMask/` – Segmentation masks for training

**Quiz:**
- `Week 3 Quiz - Detection algorithms.pdf`

---

### Week 4: Special Applications – Face Recognition and Neural Style Transfer

**Topics:**
- Face verification and recognition pipelines
- Siamese networks and triplet loss
- Neural style transfer concepts and implementation

**Assignments:**
- `Face Recognition/`
  - `Face_Recognition.ipynb`
  - Pretrained weights: `nn4.small2.v7.h5`
  - Model architecture: `inception_blocks_v2.py`
  - Utility files: `fr_utils.py`, dataset folders
- `Art Generation with Neural Style Transfer/`
  - `Art_Generation_with_Neural_Style_Transfer.ipynb`
  - Style transfer implementation: `nst_utils.py`, `public_tests.py`
  - Supporting folders: `images/`, `output/`

**Quiz:**
- `Week 4 Quiz - Special applications Face Recognition and Neural Style Transfer.pdf`

---

## Technologies Used

- Python 3.x  
- NumPy, TensorFlow, Keras  
- Jupyter Notebooks  
- Pretrained models and weight files  
- OpenCV and image processing utilities

## Notes

This repository is based on the official course materials provided by DeepLearning.AI. All content is for personal, educational use. For full access to course videos and original materials, please refer to the [official Coursera course page](https://www.coursera.org/specializations/deep-learning).
