# Attendance System with Face Detection and Spoof Proofing

## Overview

This project implements an attendance system using face detection technology combined with spoof-proofing to ensure the authenticity of the face being scanned. This system can distinguish between a real face and a digital photo, providing a reliable method for recording attendance.

## Features

- **Face Detection**: Identifies and verifies faces using state-of-the-art face recognition algorithms.
- **Spoof Proofing**: Detects and prevents attempts to use photos or videos to spoof the system.
- **Real-time Processing**: Captures and processes video feeds in real-time for immediate attendance marking.
- **User-friendly Interface**: Easy-to-use interface for users.

## Technologies Used

- **Python**: Core programming language for the project.
- **OpenCV**: Library for computer vision tasks, used for face detection.
- **Deep Learning Models**: Employed for spoof detection to differentiate between live faces and photographs.
- **Tkinter**: Standard GUI toolkit for creating the desktop application interface.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/AnantVerma-58/FaceAttendanceLogin.git
    cd FaceAttendanceLogin
    ```

2. Create and activate a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the main application:
    ```bash
    python main.py
    ```

2. The Tkinter GUI will launch. Follow the on-screen instructions to add users and record attendance.

![Real Image](samples/Real.jpeg)


## Project Structure

attendance-face-detection/
├── main.py                  # Main application file
├── SilentFaceAntiSpoofing/  # Directory for spoof proofing modules
├── utils                    # Utility scripts
├── samples                  # samples
├── requirements.txt         # Python dependencies
└── README.md                # Project README file
