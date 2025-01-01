# Gender-and-Age-Prediction-Using-CNN

Project Overview
This project leverages the UTKFace dataset, a comprehensive dataset containing over 20,000 facial images annotated with age, gender, and ethnicity. Using Convolutional Neural Networks (CNNs), the project classifies images to predict:

Gender: Male (M) or Female (F)
Age: Numerical age
Key Features:
Age range: 0 to 116 years.
Dataset includes variations in pose, facial expression, illumination, occlusion, and resolution.
Multi-task learning with two output types: gender classification and age prediction.

Dataset Information
The UTKFace dataset is a versatile dataset widely used for:

Face detection
Age estimation and progression/regression
Gender classification
Facial landmark localization
Download Link:
UTKFace Dataset on Kaggle

Objective
To build a deep learning model that can:

Classify the gender of a person from their facial image.
Predict the age of the person as closely as possible.
Achieved Metrics:
Gender Classification Accuracy: 90.00%
Age Prediction Mean Absolute Error (MAE): 6.5 years

Environment and Tools
Environment:
Platform: Kaggle
Libraries Used:
Core Libraries:
pandas
numpy
matplotlib
scikit-learn

Deep Learning Frameworks:
tensorflow
keras

Neural Network Design

Model Architecture:
The CNN model is designed with:

Convolutional Layers: To extract features from facial images.
Pooling Layers: To reduce spatial dimensions and computational complexity.
Dense Layers: For classification and regression tasks.

Output Layer:
Gender Output: A softmax activation for binary classification (M/F).
Age Output: A linear activation for numerical age prediction.

Model Performance:
Gender Accuracy: 90.00%
Age Prediction MAE: 6.5 years
