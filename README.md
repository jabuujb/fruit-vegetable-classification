# Fruit and Vegetable Classification
Computer vision project using TensorFlow/Keras to classify 51 fruit and vegetable categories and compare CNN, DNN, and MLP neural network performance.

<img width="500" height="375" alt="image" src="https://github.com/user-attachments/assets/3934dc8b-c78c-42a2-a231-d2f64dd61bc0" />

## Overview

This project was developed as part of EE 258 – Sensor Technology and Principles at San José State University.

The system classifies images into 51 categories of fruits and vegetables and then sorts them into:

- Fruits
- Vegetables
- Unknown Objects

<img width="898" height="392" alt="image" src="https://github.com/user-attachments/assets/e355ed0e-2534-4f62-836c-d50c8617457a" />


## Features

- Image classification
- CNN implementation
- DNN implementation
- MLP implementation
- Data augmentation
- Performance comparison
- Unknown object detection

<img width="500" height="375" alt="image" src="https://github.com/user-attachments/assets/bee3ab16-b490-42ac-a68f-0a50a4d1239c" />

## Technologies

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?logo=plotly&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikitlearn&logoColor=white)

## Dataset
<img width="1421" height="257" alt="image" src="https://github.com/user-attachments/assets/91e95c24-2020-4567-9d91-4e2948618b77" />
Fruit and Vegetable Image Recognition Dataset (Kaggle)
Link: https://www.kaggle.com/datasets/kritikseth/fruit-and-vegetable-image-recognition

## Results

Three neural network architectures were evaluated on a 51-class fruit and vegetable image classification problem.

| Model | Accuracy | Precision | Recall | F1-Score |
|---------|---------|---------|---------|---------|
| CNN (Baseline) | 95% | 96% | 95% | 95% |
| CNN (Improved) | 97% | 98% | 97% | 97% |
| DNN | 0% | 0% | 0% | 0% |
| MLP (Baseline) | 5% | 5% | 0% | 1% |
| MLP (Improved) | 35% | 51% | 35% | 31% |

<img width="900" height="675" alt="image" src="https://github.com/user-attachments/assets/faa39747-cb79-407e-9f3d-5ed22a296436" />

### Key Findings

- CNN achieved the highest overall performance, reaching 97% accuracy after tuning batch size and training epochs.
- Increasing the batch size from 32 to 128 and epochs from 10 to 30 improved CNN accuracy by approximately 2%.
- The MLP architecture improved substantially after tuning, increasing from approximately 5% to 35% classification performance.
- The DNN implementation successfully sorted produce categories but did not achieve meaningful classification accuracy.
- CNN-based transfer learning proved significantly more effective for image classification than MLP and DNN approaches.

### Dataset

- Original dataset: 36 classes
- Expanded dataset: 51 classes
- Final categories:
  - 21 Fruits
  - 29 Vegetables
  - 1 Unknown category
- Test Set: 474 labeled images

## Key Contributions

- Expanded the original dataset from 36 to 51 classes
- Added an Unknown category to identify non-produce images
- Implemented produce sorting into Fruit, Vegetable, and Unknown classifications
- Compared CNN, DNN, and MLP neural network architectures
- Evaluated model performance using accuracy and loss metrics

## Project Demonstration

A video demonstration of the project, model performance, and classification results is available here:

[Watch Project Demonstration](https://youtu.be/BqxeYV_6C04)

## Future Improvements

- Transfer learning with ResNet
- EfficientNet implementation
- Real-time webcam classification
- Deployment as a web application
- Object detection and localization

## Author

Justin Ogle
