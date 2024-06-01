# Drowsiness-Detection-Main

# Drowsiness Detection System for yawning as well as sleepy eyes 😴 🚫 🚗

A real-time drowsiness detection system using computer vision, OpenCV, and other relevant libraries. This system detects when a person is drowsy and alerts them to prevent accidents.

## Features

- Real-time drowsiness detection
- Alerts the user with a sound when drowsiness is detected
- Utilizes facial landmarks to detect eye closure

## Requirements

- Python 3.x
- OpenCV
- dlib
- imutils
- scipy
- numpy

## Installation

1. **Clone the repository**:
   ```sh
   git clone git@github.com:sanskaryo/Drowsiness_detection_using_dlib_and_cv.git
   cd drowsiness-detection-system



### Download the Pre-trained Shape Predictor:

1. **Download the shape predictor and extract the .dat file.**
2. **Place the `shape_predictor_68_face_landmarks.dat` file in the project directory.**

### Run the Drowsiness Detection Script:

```sh
python drowsiness_detection.py --webcam 0

## Usage

How It Works
Facial Landmark Detection:

Uses dlib’s pre-trained shape predictor model to detect facial landmarks.
The landmarks around the eyes are used to compute the Eye Aspect Ratio (EAR).
Eye Aspect Ratio (EAR):

The EAR is calculated based on the distances between the vertical eye landmarks and the horizontal eye landmarks.
When the EAR falls below a certain threshold, it indicates that the eyes are closed.
Alert Mechanism:

When the eyes remain closed for a certain number of frames, the system triggers an alert sound to wake up the user.
Detects yawning based on the distance between the upper and lower lips.


