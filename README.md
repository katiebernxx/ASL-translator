# American Sign Language Live Translator
This project uses a Convolutional Neural Network (CNN) to translate American Sign Language (ASL) letter gestures into written text. It can be used for finger spelling.
The model is trained on a dataset of ASL letters and uses a webcam to capture live video, predict the gesture, and display the corresponding text.

## Features
Real-time ASL gesture detection using your webcam
CNN model for accurate gesture recognition
Integration with OpenCV for video capture and display
MediaPipe for hand landmark detection

## Requirements
Python 3.8+
OpenCV
TensorFlow
MediaPipe
NumPy

## Usage
Clone the repository
Create and activate a virtual environment
Install the required packages
Run through the ipynb code. It builds and trains the CNN and then launches webcam translation window.

## Acknowledgements
[OpenCV](https://opencv.org/)
[TensorFlow](https://www.tensorflow.org/)
[MediaPipe](https://ai.google.dev/edge/mediapipe/solutions/guide)
