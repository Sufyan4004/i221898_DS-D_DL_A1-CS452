# Multi-Task Emotion Recognition with Deep Learning
A comprehensive implementation comparing CNN architectures for facial emotion recognition, combining expression classification with valence and arousal regression tasks.
## Overview
This project implements and compares three different CNN architectures for multi-task emotion recognition:

ResNet50 (Transfer Learning)
MobileNetV2 (Transfer Learning)
Custom CNN with attention mechanisms

The system simultaneously performs:

Expression Classification: 8-class facial expression recognition
Valence Regression: Predicting emotional positivity/negativity (-1 to +1)
Arousal Regression: Predicting emotional activation level (-1 to +1)

## Features

Multi-Task Learning: Joint training for classification and regression
Advanced Metrics: Comprehensive evaluation including RMSE, Correlation, CCC, SAGR
Data Augmentation: On-the-fly augmentation with rotation, color jitter, etc.
Early Stopping: Prevents overfitting with automatic training termination
Visualization: Sample predictions and training curve analysis
Model Comparison: Detailed performance and efficiency analysis
