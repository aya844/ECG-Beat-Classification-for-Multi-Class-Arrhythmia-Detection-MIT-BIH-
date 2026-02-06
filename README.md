# ECG-Beat-Classification-for-Multi-Class-Arrhythmia-Detection(MIT-BIH)

## Project Overview

This project focuses on **automatic multi-class classification of ECG heartbeats**
using the **MIT-BIH Arrhythmia Database**.  
The objective is to detect and classify different heartbeat morphologies directly
from raw ECG signals using machine learning techniques.

The pipeline follows a **signal-processing-aware and clinically grounded approach**,
from raw ECG recordings to beat-level classification.

---

## Objectives

- Segment ECG signals into individual heartbeats
- Classify beats into multiple arrhythmia categories
- Address class imbalance using weighted learning
- Provide interpretable error analysis via confusion matrices

---
## Signal Preprocessing Pipeline

Raw ECG signals from the MIT-BIH database are processed through a standardized
pipeline including beat-centered segmentation, bandpass filtering (0.5–40 Hz),
per-segment normalization, and class selection. The resulting ECG beat segments
are serialized to ensure reproducible and consistent model training and
evaluation.

## Machine Learning Approach

- **Model**: Random Forest Classifier
- **Why Random Forest?**
  - Robust to noise in biomedical signals
  - Handles non-linear decision boundaries
  - Interpretable compared to deep models
  - Strong baseline for medical ML tasks

---

## Dataset

- **MIT-BIH Arrhythmia Database**
- Sampling frequency: 360 Hz
- Beat annotations provided by cardiologists
- Publicly available and widely used in clinical research

---



