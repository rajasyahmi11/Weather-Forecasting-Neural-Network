# Weather Forecasting using Neural Network

## Course
BERR 3143 Artificial Intelligence

## Description
This project implements a weather forecasting system using a Neural Network (Multi-Layer Perceptron). 
The model classifies temperature conditions into three categories: Cold, Moderate, and Hot, based on 
meteorological features such as humidity, wind speed, and atmospheric pressure.

## Dataset
Weather History Dataset (Kaggle)
- Features used: Humidity, Wind Speed (km/h), Pressure (millibars)
- Target: Temperature Class (Cold, Moderate, Hot)

## Methodology
1. Load and inspect dataset
2. Select relevant features
3. Convert temperature into categorical classes
4. Split dataset into training and testing sets
5. Apply feature scaling
6. Build and train a neural network
7. Evaluate model using accuracy, confusion matrix, precision, recall, and F1-score

## Model
- Neural Network (MLP)
- Optimizer: Adam
- Loss Function: Categorical Cross-Entropy
- Activation Functions: ReLU, Softmax

## Results
- Test Accuracy: ~74%
- Evaluation metrics include confusion matrix and classification report

## Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

## Author
Raja Syahmi Afif
