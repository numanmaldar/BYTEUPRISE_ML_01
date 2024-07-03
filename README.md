# BYTEUPRISE_ML_01

# Hand Gesture Recognition
This project involves training a Convolutional Neural Network (CNN) using MobileNetV2 to recognize hand gestures and deploying it for real-time gesture detection using OpenCV and MediaPipe.

## Requirements
Python 3.8+
TensorFlow 2.x
OpenCV
MediaPipe
Pandas
NumPy

 ## Model Training
The training script uses MobileNetV2 as the base model with additional dense layers for classification. Data augmentation is applied using ImageDataGenerator. Training includes callbacks for early stopping and learning rate reduction.

## Real-Time Hand Gesture Recognition
The real-time system captures video frames using OpenCV and detects hand landmarks with MediaPipe. The hand region is extracted, preprocessed, and fed into the trained model for gesture prediction.

## Usage
Model Training: Execute the training script to train and save the model.
Real-Time Detection: Run the real-time detection script to use the webcam for gesture recognition.

## Results
The model achieves a test accuracy of approximately 91%. Real-time detection displays the predicted gesture on the video stream.
