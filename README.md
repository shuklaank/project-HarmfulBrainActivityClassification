# Harmful-Brain-Activity-Classification

## Overview

Welcome to the Harmful Brain Activity Classification project! The aim of this project is to develop models that can accurately detect and classify seizures and other types of harmful brain activity in electroencephalography (EEG) data. This task is of particular importance in critical care scenarios, where precise monitoring is crucial for effective treatment.

### Project Details

This project focuses on the classification of harmful brain activity patterns using EEG data. The dataset includes metadata, spectrograms, and expert annotations for training the models.

## Data

### Training Data

- `train.csv`: Metadata for the training set containing information about EEG samples, spectrograms, and expert annotations.
- `train_eegs/`: EEG data from overlapping samples, collected at a frequency of 200 samples per second.
- `train_spectrograms/`: Spectrograms assembled from EEG data.

### Test Data

- `test.csv`: Metadata for the test set with EEG and spectrogram information.
- `test_eegs/`: Exactly 50 seconds of EEG data for testing.

## Code

The project includes code for data preprocessing, model architecture, and evaluation metrics. The code is designed to be user-friendly and well-documented to facilitate understanding.

## Models

Experiment with different machine learning models, such as deep learning architectures or ensemble methods, to achieve accurate and robust predictions for harmful brain activity classification.

## Dataset Link
Access the dataset on Kaggle: https://www.kaggle.com/competitions/hms-harmful-brain-activity-classification/data

