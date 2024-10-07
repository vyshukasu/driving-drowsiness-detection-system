# Driving Drowsiness Detection System

## Overview

The Driving Drowsiness Detection System is a real-time application that detects drowsiness in drivers using facial landmark detection. The system utilizes the Eye Aspect Ratio (EAR) to determine whether a driver is drowsy or alert, helping to enhance road safety.

## Features

- Real-time video capture from a webcam.
- Detection of facial landmarks using dlib.
- Calculation of the Eye Aspect Ratio (EAR) to monitor drowsiness.
- Visual alerts when drowsiness is detected.

## Requirements

- Python 3.x
- OpenCV
- dlib
- SciPy

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/vyshukasu/driving-drowsiness-detection-system.git
   cd driving-drowsiness-detection-system
2. pip install opencv-python dlib scipy
3.Download the shape_predictor_68_face_landmarks.dat file from dlib's model repository
and place it in the project directory.
  
