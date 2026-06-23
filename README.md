# Consumer Decision Analysis using Neuromarketing Data

## Overview

Consumer Decision Analysis using Neuromarketing Data is a Deep Learning project that leverages EEG (Electroencephalography) and eye-tracking signals to analyze consumer behavior and predict hidden purchase interest, cognitive overload, and decision reversal patterns. The project employs multiple neural network architectures, including MLP, 1D CNN, LSTM, GRU, and CNN-LSTM hybrid models, to uncover latent consumer insights beyond traditional survey-based methods.

---

## Problem Statement

Traditional marketing research often relies on questionnaires and self-reported feedback, which may not always reflect genuine consumer intent. This project explores how physiological and behavioral signals can be utilized to predict consumer purchase intent, identify cognitive overload, and anticipate decision reversals during the decision-making process.

---

## Objectives

### Hidden Interest Prediction
Identify consumers who are genuinely interested in a product, even when explicit responses may not reveal that interest.

### Cognitive Overload Detection
Detect situations where excessive information or complexity negatively impacts consumer decision-making.

### Decision Reversal Prediction
Predict whether consumers are likely to change their initial decisions during the purchasing journey.

---

## Dataset

The dataset consists of multimodal neuromarketing data collected from consumer interactions.

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

### Behavioral Labels
- Hidden Interest
- Cognitive Overload
- Decision Reversal

---

## Methodology

### Data Preprocessing
- Missing value handling
- Data cleaning
- Feature normalization and scaling
- Exploratory Data Analysis (EDA)
- Class distribution analysis

### Feature Engineering
- Statistical feature extraction
- Correlation analysis
- Signal-based feature transformation
- Feature selection and optimization

### Deep Learning Models

- Multi-Layer Perceptron (MLP)
- 1D Convolutional Neural Network (1D CNN)
- Long Short-Term Memory (LSTM)
- Gated Recurrent Unit (GRU)
- CNN + LSTM Hybrid Network

---

## Results

| Task | Best Model | Accuracy |
|--------|--------|--------|
| Hidden Interest Prediction | MLP | **91.0%** |
| Cognitive Overload Detection | 1D CNN | **95.9%** |
| Decision Reversal Prediction | 1D CNN | **95.2%** |

The proposed models achieved strong predictive performance across all tasks. The 1D CNN emerged as the best-performing architecture for Cognitive Overload and Decision Reversal prediction, while the MLP achieved the highest accuracy for Hidden Interest prediction.

---

## Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## Key Learnings

- Deep learning for physiological signal analysis
- Multimodal learning using EEG and eye-tracking data
- Consumer behavior prediction using neural networks
- Feature engineering and preprocessing for behavioral datasets
- Comparative evaluation of deep learning architectures
- Neuromarketing analytics and decision intelligence

---

## Future Improvements

- Transformer-based architectures for sequential signal modeling
- Explainable AI (XAI) techniques for model interpretability
- Real-time consumer state prediction
- Interactive analytics dashboard
- Advanced multimodal fusion techniques
- Integration with recommendation and personalization systems
