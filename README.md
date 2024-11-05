# Human-Activity-Recognition-from-Images

This project performs image classification on a dataset containing over 12,000 images of 15 different human activity classes. The main goal is to classify human actions to aid in behavior analysis.

Key Tasks
Exploratory Data Analysis (EDA):

Overview of the dataset: Displays the number of images per class and summarizes image size distributions.
Visualizations: Includes class distribution bar charts and sample images from each class for better understanding.
Class Imbalance Analysis: Checks for class imbalances and proposes solutions such as data augmentation and resampling to address any detected imbalances.
Feature Extraction:

Applies Histogram of Oriented Gradients (HOG) and color histogram methods to extract essential features for each image.
Provides visualizations of HOG features and color histograms, showcasing the effectiveness of these features in representing the images.
Model Selection and Training:

Implements models including Naive Bayes, Decision Tree, Random Forest, Perceptron, and XGBoost to classify the activities based on extracted features.
Utilizes an 80:20 train-test split and evaluates models on accuracy.
Conducts hyperparameter tuning for HOG feature extraction and compares model performances to identify the best approach.
This repository includes code, visualizations, and analysis results. It provides insights into human activity recognition through image classification and a comparative study of traditional and ensemble classifiers.

