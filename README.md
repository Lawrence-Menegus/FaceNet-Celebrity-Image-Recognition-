# FaceNet Celebrity Image Identification

## Overview
This project uses the FaceNet deep learning algorithm for face recognition to identify celebrities in images. The algorithm extracts high-dimensional feature vectors (embeddings) from face images and uses them for matching and identification.

## Download Packages: 
<p> pip install mtcnn</p>
<p> pip install tourchvision</p>
<p> pip install facenet-pytorch</p>
<p> pip install scikit-learn</p>

## Features
- Face Extraction: Uses the MTCNN algorithm to detect and extract faces from images.
- Dataset Preparation: Loads a dataset of face images, extracts faces, and prepares the dataset for training and testing.
- Model Training: Defines a custom FaceNet model based on ResNet-101 and trains it using the dataset.
- Embedding Extraction: Uses the trained model to extract embeddings from face images.
- SVM Classification: Trains an SVM classifier using the normalized embeddings for face recognition.
- Hyperparameter Tuning: Uses GridSearchCV to tune hyperparameters of the SVM classifier.
- Evaluation: Evaluates the trained SVM classifier on a test dataset and calculates accuracy.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Lawrence-Menegus/FaceNet-Celebrity-Image-Recognition-.git
   cd facenet-celebrity-identification

## Install dependencies:
pip install -r requirements.txt

Download the 5-celebrity-faces dataset from Kaggle and extract it into the project directory.

## Usage:
Run the training script to train the FaceNet model and the SVM classifier:

python train.py

### Run the evaluation script to evaluate the trained model on the test dataset:

python evaluate.py

<p> Use the provided functions to extract embeddings from new images and classify them using the trained model. </p>

## Contributors 
<p> By Lawrence Menegus</p>
