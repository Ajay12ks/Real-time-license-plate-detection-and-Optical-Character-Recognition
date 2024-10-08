# Automated License Plate Recognition (ALPR) System

## Overview
This project implements a real-time Automated License Plate Recognition (ALPR) system using OpenCV and Tesseract OCR. The system can detect and recognize license plates using a webcam, displaying the results in real-time.

## Features
- **Real-time License Plate Detection**: Utilizes OpenCV’s Haar Cascade Classifier to detect license plates.
- **Optical Character Recognition (OCR)**: Employs Tesseract OCR to extract text from the detected license plates.
- **Live Video Capture**: Processes frames from a webcam to provide immediate feedback on detected license plates.
- **User Interaction**: Press the **Enter** key to display recognized characters in the terminal, or press **q** to exit the application.

## Technology Stack
- **Python**: Primary programming language.
- **OpenCV**: Library for computer vision and image processing.
- **Tesseract OCR**: Optical character recognition engine for extracting text from images.
- **cvlib**: Simplifies the implementation of computer vision tasks.

## Installation

### Prerequisites
1. Python 3.x installed on your system.
2. Install required libraries:
   ```bash
   pip install opencv-python opencv-python-headless numpy pytesseract cvlib
