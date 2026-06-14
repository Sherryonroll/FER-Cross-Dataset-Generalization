# Cross-Dataset Generalization of Lightweight Facial Emotion Recognition for Driver Monitoring

This project trains a SqueezeNet 1.1 facial emotion recognition model on KMU-FED and tests it on unseen datasets such as KDEF and FER2013 without retraining.

## Main Experiment

1. Train and test on KMU-FED to get the baseline.
2. Save the trained KMU-FED model.
3. Test the same model on KDEF and FER2013.
4. Compare accuracy, precision, recall, F1-score, confusion matrix, and accuracy drop.

## Datasets

Datasets are not uploaded to GitHub due to size and access restrictions.

Expected local dataset structure:

```text
data_raw/
├── KMU_FED/
├── KDEF/
└── FER2013/