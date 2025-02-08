# Speech_Emotion_Detection

## Overview

Speech Emotion Detection (SED) aims to recognize emotions such as happiness, disgust, sadness, surprise, and neutrality from audio data using Artificial Intelligence (AI). The challenge in this task arises due to the diversity in audio data, including variations in speaker characteristics, recording environments, and audio quality. This can lead to difficulties in generalizing models across different contexts and populations, affecting their performance.

## Problem Statement

The primary challenge in speech emotion detection is the ability to capture the variability in audio data. The factors that contribute to this problem include:

- Speaker diversity
- Variations in audio recording environments
- Differences in audio quality

These challenges hinder the generalization of machine learning models, making it difficult to achieve consistent performance across various datasets and contexts.

## Approach

This project tackles these issues by combining multiple datasets and adopting a multimodal approach. The approach involves:

- Data augmentation
- Feature extraction
- Ensemble learning using traditional machine learning models

The study compares the performance of simple classification models like Support Vector Machine (SVM) and Random Forest (RF) with more complex neural network models, with an emphasis on using ensemble learning techniques to improve model accuracy.

### Key Components

- **Datasets**: A combination of diverse speech emotion datasets to improve the generalizability of the model.
- **Data Augmentation**: Applied to increase the size and variability of the training dataset, improving model robustness.
- **Feature Extraction**: Various audio features like Mel-Frequency Cepstral Coefficients (MFCC), chroma features, and spectral contrast were extracted from the raw audio data.
- **Model Comparison**: Simple machine learning models (SVM, RF) were compared with neural network models to evaluate their effectiveness.

## Results

The research focused on ensemble learning techniques using SVM and RF, which yielded the best accuracy of **81%**. The results demonstrate the potential for improving the generalization and reliability of speech emotion detection models by combining traditional machine learning techniques with data augmentation and feature extraction.

## Installation

To run the project, make sure you have the following Python libraries installed:

```bash
pip install -r requirements.txt
