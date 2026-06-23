# Consumer Decision Analysis using Neuromarketing Data

## Overview

Consumer Decision Analysis using Neuromarketing Data is a Machine Learning and Deep Learning project that leverages EEG (Electroencephalography) and eye-tracking signals to analyze consumer behavior and predict hidden purchase interest, cognitive overload, and decision reversal patterns. By combining physiological and behavioral indicators, the project provides deeper insights into consumer decision-making beyond traditional survey-based approaches.

---

## Problem Statement

Traditional marketing research often relies on self-reported feedback, which may not accurately capture genuine consumer intent. This project explores how physiological and behavioral signals can be used to identify latent consumer states, predict purchase intent, detect cognitive overload, and anticipate decision reversals during the consumer decision-making process.

---

## Dataset

The dataset consists of multimodal neuromarketing features derived from consumer interactions.

### EEG Features
- Attention metrics
- Cognitive workload indicators
- Emotional response measurements
- Brain activity patterns

### Eye-Tracking Features
- Fixation duration
- Saccade patterns
- Visual attention metrics
- Gaze behavior measurements

### Behavioral Variables
- Purchase decisions
- Hidden interest indicators
- Cognitive overload labels
- Decision reversal labels

---

## Objectives

The project focuses on three key prediction tasks:

### 1. Hidden Interest Prediction
Identify consumers genuinely interested in a product even when explicit responses may differ.

### 2. Cognitive Overload Detection
Detect situations where excessive information or complexity impacts consumer decision-making.

### 3. Decision Reversal Prediction
Predict whether consumers are likely to change their initial decisions during the purchasing process.

---

## Methodology

### Data Preprocessing
- Missing value handling
- Data cleaning
- Feature scaling and normalization
- Exploratory Data Analysis (EDA)
- Class distribution analysis

### Feature Engineering
- Statistical feature extraction
- Correlation analysis
- Feature selection
- Signal-based feature transformation

### Models Implemented

#### Machine Learning Models
- Random Forest
- Logistic Regression
- Support Vector Machine (SVM)

#### Deep Learning Models
- Multi-Layer Perceptron (MLP)
- 1D Convolutional Neural Network (1D CNN)
- Long Short-Term Memory (LSTM)
- Gated Recurrent Unit (GRU)

---

## Results

| Task | Best Model | Accuracy |
|--------|--------|--------|
| Hidden Interest Prediction | MLP | **91.0%** |
| Cognitive Overload Detection | 1D CNN | **95.9%** |
| Decision Reversal Prediction | 1D CNN | **95.2%** |

The proposed models achieved strong predictive performance across all tasks. The 1D CNN achieved 95.9% accuracy for Cognitive Overload Detection and 95.2% accuracy for Decision Reversal Prediction, while the MLP achieved 91.0% accuracy for Hidden Interest Prediction.

---

## Tech Stack

- Python
- TensorFlow
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Key Learnings

- Multimodal data fusion using EEG and eye-tracking signals
- Consumer behavior prediction using Machine Learning and Deep Learning
- Feature engineering for physiological signal analysis
- Model optimization and comparative evaluation
- Behavioral analytics using neuromarketing data
- Predictive modeling for consumer decision-making

---

## Future Improvements

- Transformer-based architectures for sequential signal modeling
- Explainable AI (XAI) techniques for model interpretability
- Real-time consumer state prediction
- Interactive analytics dashboard
- Integration with recommendation systems
- Advanced multimodal learning approaches
