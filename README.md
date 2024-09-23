# Hand Gesture Recognition System

## Overview
This project implements a **hand gesture recognition system** using a webcam, leveraging **MediaPipe** for detecting hand landmarks and a pre-trained **TensorFlow model** for classifying gestures. The gestures are displayed in real-time on the webcam feed.

## Features
- Real-time hand gesture recognition using a webcam.
- Gesture classification based on a pre-trained model.
- Supported gestures include:
  - Okay
  - Peace
  - Thumbs up
  - Thumbs down
  - Call me
  - Stop
  - Rock
  - Live long
  - Fist
  - Smile

## Requirements
- Python 3.x
- OpenCV
- NumPy
- MediaPipe
- TensorFlow

## Setup and Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Samuel-0316/hand-gesture-recognition.git
   cd hand-gesture-recognition
2. Install the required packages:
   ```bash
   pip install opencv-python numpy mediapipe tensorflow
3. Download or create a pre-trained model and save it as mp_hand_gesture.h5

4. Create a text file named gesture.names containing the class names of the gestures.

## Usage
-> Run the script to start the gesture recognition:
  ```bash
  python your_script_name.py
  ```
Make sure your webcam is connected. The recognized gesture will be displayed on the video feed. Press q to exit the application.

## Contributing
Feel free to submit issues, fork the repository, or create pull requests. Contributions are welcome!
