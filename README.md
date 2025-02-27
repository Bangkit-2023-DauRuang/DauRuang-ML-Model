# Machine Learning for DauRuang

## Overview
This repository contains the **machine learning** component of the Bangkit capstone project, **DauRuang**. DauRuang is a mobile application designed to facilitate the collection of recyclable waste and provide rewards to users, promoting **sustainable living**.

## About DauRuang
DauRuang helps users easily manage their recyclable waste through the following workflow:
1. Users scan their recyclable waste using an **Android** device.
2. The application classifies the type of waste using a **machine learning model**.
3. Users can select a recycling center where they want to sell the waste.
4. The waste is picked up from the user's location and delivered to the selected recycling center.
5. Users earn points based on the amount of waste collected.
6. Collected points can be exchanged for rewards.

## Machine Learning Component
The **machine learning** aspect of this project focuses on **waste image classification**. The model was developed in collaboration with the **machine learning learning path** teammates.

### Model Development
- **Transfer Learning**: We used TensorFlow's **transfer learning** approach to train the model efficiently.
- **Model Deployment**: The trained model was converted to **TensorFlow Lite (TFLite)** for integration into the mobile application.

## Tech Stack
- **TensorFlow** (for training the ML model)
- **TensorFlow Lite** (for model deployment on Android)
- **Python** (for preprocessing and model training)
