# Human-Activity-Recognition-from-Images

This project performs image classification on a dataset containing over 12,000 images of 15 different human activity classes. The main goal is to classify human actions to aid in behavior analysis.

## Key Tasks
Exploratory Data Analysis (EDA):

Overview of the dataset: Displays the number of images per class and summarizes image size distributions.
Visualizations: Includes class distribution bar charts and sample images from each class for better understanding.

## Feature Extraction:

Applies Histogram of Oriented Gradients (HOG) and color histogram methods to extract essential features for each image.
Provides visualizations of HOG features and color histograms, showcasing the effectiveness of these features in representing the images.

## Model Selection and Training:

Implements models including  Random Forest and XGBoost to classify the activities based on extracted features.
Utilizes an 80:20 train-test split and evaluates models on accuracy.
Conducts hyperparameter tuning for HOG feature extraction and compares model performances to identify the best approach.
This repository includes code, visualizations, and analysis results. It provides insights into human activity recognition through image classification and a comparative study of traditional and ensemble classifiers.

Dataset Google drive link- https://drive.google.com/drive/folders/1h1fM4lD-n8-MgJDbLymt4_4lxO7y3Yrf?usp=drive_link



