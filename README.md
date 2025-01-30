# Sleep and Wake Detection Project

This project focuses on detecting sleep and wake states using the DDD dataset from Kaggle. The implementation is based on ensemble learning techniques and was developed as part of the Image Processing course at the University of Guilan under the guidance of DR.Akushide.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)

## Introduction
The goal of this project is to classify sleep and wake states using machine learning techniques. The DDD dataset from Kaggle was used for training and evaluation. The project leverages ensemble learning to improve the accuracy of the classification model.

## Dataset
The DDD dataset is available on Kaggle: [DDD Dataset Link]([https://www.kaggle.com/datasets/...](https://www.kaggle.com/datasets/ismailnasri20/driver-drowsiness-dataset-ddd)). It contains **41,793 samples** of sleep and wake state data. The dataset was split as follows:
- **70% for training**: Divided among 5 models for ensemble learning.
- **20% for validation**: Divided among 5 models for ensemble learning.
- **10% for testing**: Used to evaluate the final model.

## Methodology
The project uses an **ensemble learning approach** with the following steps:
1. **Data Splitting**: The dataset was split into training (70%), validation (20%), and testing (10%) sets.
2. **Model Training**: Five CNN models were trained on the training set.
3. **Validation**: The models were validated using the validation set.
4. **Ensemble Learning**: The predictions from the five models were combined to improve accuracy.
5. **Testing**: The final model was evaluated on the test set.

## Results
   The final model achieved the following results:
   
   **Accuracy**: 99.88%
   
   **Confusion Matrix**:
   
   ![image](https://github.com/user-attachments/assets/be3a8213-a2e4-4b9d-ae98-ba5ca5c0fb57)
