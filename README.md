# Self-Driving Car Using Deep Learning

This project demonstrates a self-driving car model trained using deep learning techniques, with data collected from the [Udacity Car Driving Simulator](https://github.com/udacity/self-driving-car-sim). The model learns to autonomously drive in the simulator environment by predicting steering angles based on camera images.

## 🚗 Project Overview

The objective is to build a deep learning model that mimics human driving behavior by processing visual input from a simulated environment and producing appropriate steering commands.

## 📁 Dataset

- Data was collected using the Udacity simulator's training mode.
- The dataset includes center, left, and right camera images along with corresponding steering angles.

## 🧠 Model Architecture

- A convolutional neural network (CNN) inspired by Nvidia’s end-to-end self-driving car model.
- Layers include Conv2D, Dropout, and Dense layers for robust feature extraction and prediction.

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- Numpy
- Matplotlib
- Udacity Self-Driving Car Simulator

## 🏁 How to Run

1. Clone this repository.
2. Collect driving data using the Udacity simulator.
3. Train the model:
   ```bash
   python model.py
