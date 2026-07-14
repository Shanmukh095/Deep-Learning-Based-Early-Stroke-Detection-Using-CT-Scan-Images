# Early Brain Stroke Detection Using CT Scan Images with BiLSTM

## Overview

This project presents an intelligent deep learning framework for the early detection of brain stroke using CT scan images. The proposed approach combines deep feature extraction, feature optimization, and sequence learning to accurately classify CT scans as **Normal** or **Stroke**. The objective is to assist healthcare professionals by providing a reliable and efficient computer-aided diagnosis system for early stroke detection.

## Features

* Automated brain stroke detection from CT scan images.
* Deep feature extraction using **InceptionV3**.
* Feature normalization with **StandardScaler**.
* Dimensionality reduction using **Principal Component Analysis (PCA)**.
* Optimal feature selection using a **Genetic Algorithm (GA)**.
* Classification using multiple machine learning and deep learning models, with **BiLSTM** achieving the best performance.
* Performance evaluation using accuracy, precision, recall, F1-score, ROC-AUC, and confusion matrix.

## Project Pipeline

1. Load and preprocess CT scan images.
2. Split the dataset into training and testing sets.
3. Extract deep features using InceptionV3.
4. Normalize features using StandardScaler.
5. Reduce feature dimensions using PCA.
6. Select the most relevant features using a Genetic Algorithm.
7. Train and compare multiple classifiers.
8. Use the BiLSTM model for final stroke prediction.
9. Evaluate model performance using standard classification metrics.

## Technologies Used

* Python
* TensorFlow / Keras
* Scikit-learn
* NumPy
* OpenCV
* Matplotlib
* Pandas

## Applications

* Computer-aided diagnosis of brain stroke.
* Early screening and risk assessment.
* Clinical decision support systems.
* Medical image analysis research.

## Future Enhancements

* Multi-class stroke classification.
* Integration with real-time hospital diagnostic systems.
* Explainable AI (XAI) techniques for model interpretability.
* Deployment as a web or mobile application for clinical use.
