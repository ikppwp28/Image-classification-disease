# Coding Classification Disease using Tensorflow (Transfer Learning)

This repository contains two projects focused on disease classification using deep learning techniques and TensorFlow. Each project is designed to address a specific medical classification problem. Below are the details of each project:

## Project 1: Pneumonia Classification - Normal vs. Pneumonia

![Pneumonia Image](https://www.mayoclinic.org/-/media/kcms/gbs/patient-consumer/images/2016/05/18/13/02/ww5r032t-8col-jpg.jpg)

In the first project, we tackle the critical task of classifying chest X-ray images into two categories: normal and pneumonia. This binary classification is vital for early detection and diagnosis of pneumonia, a common respiratory disease.

### Transfer Learning with MobileNet

We employ the power of transfer learning by using MobileNet as our base model. Transfer learning allows us to leverage pre-trained neural network architectures to boost the performance of our classifier.

Key Highlights:
- Pre-processing and data augmentation for chest X-ray images
- Fine-tuning MobileNet for pneumonia classification
- Model evaluation using accuracy and loss

## Project 2: Brain Tumor Classification

![Brain Tumor Image](https://www.mayoclinic.org/-/media/kcms/gbs/patient-consumer/images/2014/10/30/15/17/mcdc7_brain_cancer-8col.jpg)

The second project focuses on brain tumor classification. We explore the effectiveness of multiple transfer learning architectures, including MobileNet, InceptionV3, ResNet152, and VGG16, in distinguishing between different types of brain tumors.

### Comparative Analysis of Transfer Learning Models

In this project, we conduct an in-depth comparative analysis of various pre-trained models to identify the best-performing architecture for brain tumor classification.

Key Highlights:
- Data preprocessing and augmentation for brain tumor images
- Transfer learning with MobileNet, InceptionV3, ResNet152, and VGG16
- Performance comparison using accuracy and loss
