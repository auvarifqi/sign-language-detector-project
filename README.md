# Sign Language Detector Project

This project focuses on detecting sign language gestures using computer vision techniques with OpenCV and machine learning.

## Overview

The `sign_language_detector.py` script is designed to:

- **Collect Data**: Capture images from your webcam to build a dataset for different sign language classes.
- **Train Models**: Use the collected data to train machine learning models capable of recognizing sign language gestures.
- **Real-Time Detection**: Implement real-time gesture recognition using the trained models.

## Features

- **Easy Data Collection**: Streamlined process to gather images for multiple gesture classes.
- **Customizable Classes**: Easily adjust the number of gesture classes and dataset size.
- **Real-Time Recognition**: Detect and interpret sign language gestures in real-time.

## Requirements

- Python 3.x
- OpenCV (`opencv-python`)
- Scikit-Learn
- Mediapipe

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/sign-language-detector-project.git
   ```

2. **Navigate to the Project Directory**

   ```bash
   cd sign-language-detector-project
   ```

3. **Create a Virtual Environment (Optional but Recommended)**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

4. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```
