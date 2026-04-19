# Handwritten Mathematical Symbol Classification

## Overview
This project develops machine learning models to classify handwritten mathematical symbols using image processing and classification techniques.

## Features
- Implemented SVM and ANN models for multi-class classification
- Applied feature extraction techniques (HOG, LBP, raw pixels)
- Compared model performance across different feature-classifier combinations
- Evaluated models using accuracy and confusion matrix

## Tech Stack
Python, NumPy, OpenCV, Scikit-learn, Matplotlib

## Results
The best performing model was SVM with HOG features, achieving the highest accuracy of 0.9860. Overall, HOG features performed better than LBP and raw pixel representations for both classifiers.

### Model Comparison
<img width="1231" height="285" alt="image" src="https://github.com/user-attachments/assets/22cf9df7-b236-4247-9e9f-9c7664f2e465" />

### Confusion Matrix
The confusion matrix shows that most classes were correctly classified, with only minor misclassifications between visually similar symbols.
<img width="1358" height="711" alt="image" src="https://github.com/user-attachments/assets/bca97dfb-5dc0-4ff7-8295-2f0449ded2ad" />

## Key Insight
HOG feature extraction significantly improves classification performance by capturing edge and shape information, making it more suitable for handwritten symbol recognition.

## Report
Detailed analysis is available in the project report (PDF included in repository).

## Author
Deepanshi Bansal
Bachelor of Computer Science (Data Analytics & AI)
