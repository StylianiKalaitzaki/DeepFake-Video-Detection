# Video Face Extraction and Classification

This repository contains a Python pipeline for extracting faces from video frames and classifying videos as "real" or "fake." The pipeline uses MTCNN for face detection and EfficientNetB0 for classifying images.

## Features
- **Face Extraction:** Uses MTCNN to detect and extract faces from video frames.
- **Dataset Preparation:** Converts video frames into a balanced dataset of real and fake faces.
- **Model Training:** Utilizes EfficientNetB0 to classify extracted faces as "real" or "fake."
- **Evaluation:** Evaluates the model's performance using accuracy, precision, recall, F1 score, and confusion matrix.

## Dataset
The dataset used is from the [DeepFake Detection Challenge on Kaggle](https://www.kaggle.com/competitions/deepfake-detection-challenge/data). Only the first smaller chunk of 400 videos has been used for this project.


## Requirements
- Python 3.x
- Keras
- TensorFlow
- OpenCV
- MTCNN
- EfficientNet for TensorFlow Keras
