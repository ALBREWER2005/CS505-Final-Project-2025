# CS505-Final-Project-2025

# Sleep Health Prediction using Machine Learning

This project explores machine learning models to predict health outcomes based on sleep and lifestyle-related factors. It was created for the CS505 final project.

## Dataset

**Sleep Health and Lifestyle Dataset**
- 400 samples, 13 features
- Variables include:
  - Demographics: Age, Gender, Occupation
  - Health: BMI Category, Blood Pressure, Heart Rate
  - Lifestyle: Physical Activity, Daily Steps, Stress Level
  - Sleep: Sleep Duration, Sleep Quality, Sleep Disorder

## Goals

1. Classify sleep disorders (None, Insomnia, Sleep Apnea)
2. Predict sleep quality (scale 1–10)
3. Predict stress level (scale 1–10)

## Tools and Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- TensorFlow / Keras
- Scikit-learn

## Models

### 1. Sleep Disorder Classification

- Type: Multi-class classification
- Architecture: 2 hidden layers → softmax
- Loss: Categorical Crossentropy
- Optimizer: Adam

**Results**
- Training accuracy: 87%
- Validation accuracy: 22.5%
- Test accuracy: 7.4%
- Test loss: 1.31

### 2. Sleep Quality Regression

- Type: Regression
- Architecture: 2 hidden layers → 1 output neuron
- Loss: Mean Squared Error (MSE)
- Metrics: MAE, MSE

**Results**
- Test MSE: 24.54
- Test MAE: 4.76

### 3. Stress Level Regression

- Type: Regression
- Architecture: Similar to sleep quality model
- Loss: Mean Squared Error (MSE)
- Metrics: MAE, MSE

**Results**
- Test MSE: 22.46
- Test MAE: 4.13

## File Structure

