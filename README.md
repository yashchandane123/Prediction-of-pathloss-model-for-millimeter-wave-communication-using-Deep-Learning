# Prediction of Path Loss Model for Millimeter Wave Communication using Deep Learning

This project involves predicting the path loss in millimeter wave (mmWave) communication systems using a Deep Learning-based approach. The focus is on utilizing a Convolutional Neural Network (CNN) for accurate prediction, leveraging a dataset featuring key parameters such as frequency, distance, path loss, and the number of base stations.

## Key Details

- **Frequency:** The model is designed for mmWave communication at **28 GHz**, a commonly used frequency in 5G networks.
- **Dataset Parameters:**
  - **Distance:** The distance between the transmitter and receiver.
  - **Path Loss:** The attenuation of signal power as it propagates through space.
  - **Number of Base Stations:** A key factor influencing the network's coverage and path loss.
- **Deep Learning Model:** The project uses a **Convolutional Neural Network (CNN)** for its ability to capture spatial features and relationships in the dataset.

## Features

- Accurate prediction of path loss based on input parameters.
- Demonstrates the application of CNNs in wireless communication modeling.
- Focused on enhancing the performance and reliability of 5G mmWave networks.

## How It Works

1. **Dataset Preparation:** The dataset includes measurements of path loss for various distances and configurations of base stations at 28 GHz.
2. **Model Training:** A CNN model is trained on the dataset to learn the relationship between the input parameters and the path loss.
3. **Prediction:** The trained model predicts the path loss for given distances and base station configurations, enabling better network planning and optimization.

## Applications

- 5G network planning and optimization.
- Research on mmWave communication performance.
- Development of advanced path loss models for wireless systems.

## Requirements

- Python
- TensorFlow/Keras
- Required libraries for data preprocessing and visualization (e.g., NumPy, Pandas, Matplotlib).

## Usage

1. Prepare the dataset with the required parameters.
2. Train the CNN model using the provided script.
3. Use the trained model to predict path loss for new configurations.

This approach provides a robust framework for leveraging deep learning in mmWave communication system design.

