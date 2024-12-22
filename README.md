# Sign Language Detection  
<img src='https://miro.medium.com/v2/resize:fit:828/format:webp/0*EC2QFI9soQV-qMlY' width=40% height=20%>

This repository contains my project on **Sign Language Detection** using two different approaches:  

1. **CNN-Based Approach**  
2. **Mediapipe + Random Forest Approach**  

## Table of Contents  
- [Introduction](#introduction)  
- [Approach 1: CNN](#approach-1-cnn)  
- [Approach 2: Mediapipe + Random Forest](#approach-2-mediapipe--random-forest)  
## Introduction  
Sign language detection is a critical application in making communication more inclusive. This project explores two distinct methods to recognize hand gestures and detect alphabets.  

## Approach 1: CNN  

In this approach, I trained a **Convolutional Neural Network (CNN)** on preprocessed sign language images.  
### Key Steps:  
- **Gaussian Blur Filters**: To minimize background influence.  
- **Data Augmentation**: Techniques like zooming, flipping, and rotation.  
- **Histogram Equalization**: To enhance image contrast.  

### Example Outputs:  

| Prediction1:         | Prediction2:  | Prediction3: |  
|-----------------------|---------------------|---------------------|  
| ![Input](https://drive.google.com/uc?id=1f3DQaPfpIYXEc6T8GTG1DKMMBGEJfTyQ) | ![Preprocessed](https://drive.google.com/uc?id=1ergYoeKt4kwmoFwRuZ6WYaQslbG2cxNJ) | ![Prediction](https://drive.google.com/uc?id=1XhyQlxnq_pohnYyNV9U4-2nOdbZ_uAKz) |  

---

## Approach 2: Mediapipe + Random Forest  

This approach uses **Mediapipe** to extract hand landmarks and a **Random Forest classifier** for gesture recognition.  
### Key Steps:  
- **Landmark Extraction**: Using Mediapipe to extract hand and finger positions.  
- **Feature Storage**: Saving the landmarks for classification.  
- **Random Forest Classifier**: Training the model on the extracted features.  

### Example Outputs:  

| Prediction1:         | Prediction2:  | Prediction3: |  
|-----------------------|---------------------|---------------------|  
| ![Input](https://drive.google.com/uc?id=18VwOVxOUhPnKWa9SWIbkRTLeWWDUK9GA) | ![Preprocessed](https://drive.google.com/uc?id=1Tcu9jAHwfPJ7lVWRXgU9fuQhYOY7Uv_z) | ![Prediction](https://drive.google.com/uc?id=1_FxlEO7jlp26UnYz5diXF-P7RQW6cwXS) |  

---


