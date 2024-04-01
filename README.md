# Self Project Computer Vision

Here is a collection of self-projects in Computer Vision using PyTorch to continue my learning from the Computer Vision Bootcamp at the Indonesia AI and to enhance problem-solving skills in various Computer Vision applications.

## 1. Gender Classification

This project utilizes the CelebA dataset consisting of 5000 photos containing a mix of males and females. The goal of this project is to experiment with building gender classification models using several pre-trained models. The models used include Inception V3, ResNet 50, and EfficientNet B2. This project contains Exploratory Data Analysis (EDA), Data Preparation, Data Preprocessing, Model Building, Training, Evaluation, and Predictions.

## 2. Food Classification

* This is a computer vision project to create food classification. The dataset used is Food 101. Only a portion of the dataset is taken, namely pizza, steak, and sushi. This project uses the pretrained ResNet 50 model.
* In addition to creating a classification model, this project also aims to compare two types of transfer learning methods, namely fine-tuning and fix feature extractor. Fine-tuning involves retraining all parameters of the pretrained model on a different dataset to adjust its weights. Fix feature extractor only trains the modified fully connected layer, while other parameters are not trained again.
* Based on existing theories, the fine-tuning method may cause overfitting because all parameters are retrained. This also results in longer training processes. To address this overfitting, it may be necessary to modify some layers, including the fully connected layer. The fix feature extractor method is considered more practical, simple, and easy to use because only the fully connected layer is modified and trained, thus avoiding overfitting.
* The results of this comparison have been demonstrated in this experimental documentation.
