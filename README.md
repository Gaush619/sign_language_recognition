# Hand Gesture Recognition  

This project implements a hand gesture recognition system using OpenCV, MediaPipe, and a trained machine learning model. The model predicts letters of the alphabet (A-Z) based on hand landmarks captured via a webcam.

## Features  
- Uses MediaPipe for real-time hand tracking.  
- Predicts hand gestures corresponding to alphabets A-Z.  
- Draws hand landmarks and bounding boxes for visualization.  
- Loads a trained model from `model.p` for gesture classification.  

## Requirements  

Ensure you have the following dependencies installed:  

```bash
pip install opencv-python mediapipe numpy pickle scikit-learn
