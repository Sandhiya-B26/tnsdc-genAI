# tnsdc-genAI
# Real-time Face Detection using OpenCV

This project focuses on real-time face detection using OpenCV, a popular computer vision library in Python. The objective is to detect faces from a live video stream captured by a webcam and draw bounding boxes around them.

## Overview

Face detection is a fundamental task in computer vision with applications in various domains such as security, surveillance, and facial recognition systems. This project utilizes OpenCV's Haar Cascade classifier to detect faces in real-time from a live video feed.

## Key Features

- **Real-time Detection**: Faces are detected in real-time from the live video stream captured by the webcam.
- **Bounding Box Visualization**: Detected faces are highlighted with bounding boxes to visually indicate their positions.
- **Simple User Interface**: The application provides a simple and intuitive interface for real-time face detection.

## Usage

1. **Haar Cascade Configuration**: Ensure the correct path to the Haar Cascade XML file is provided in the script (`haar_cascade.xml`).
2. **Face Detection**: Run the script to initiate face detection from the live video feed captured by the webcam.
3. **Real-time Visualization**: Detected faces will be highlighted with bounding boxes in real-time.
4. **Interaction**: No user interaction is required during the face detection process. Press the 'q' key to exit the application.

## Dependencies

- OpenCV

## File Structure

- `face_detection.py`: Python script containing the code for real-time face detection using OpenCV's Haar Cascade classifier.
- `haar_cascade.xml`: XML file containing the pre-trained Haar Cascade classifier for face detection.

## Contributions

Contributions to this project are welcome! Whether it's bug fixes, enhancements, or new features, feel free to open issues or submit pull requests to improve the functionality and performance of this face detection project.

