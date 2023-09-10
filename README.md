# Automatic-Number-Plate-Recognition
This repository contains a Python project for Car Number Plate Detection and Recognition using OpenCV and EasyOCR. Automatic Number Plate Recognition (ANPR) is a critical technology used in various applications, including traffic management, parking systems, and law enforcement. This project demonstrates how to implement a system to detect and recognize number plates from a webcam feed.


Before you begin, ensure you have met the following requirements:
- Python 3.x installed on your system.
- Required libraries: OpenCV, EasyOCR. You can install them using pip:
      pip install opencv-python , 
      pip install easyocr.

How it Works
  1. Webcam Feed: The script captures frames from your webcam in real-time.
  2. Preprocessing: Preprocessing techniques are applied to enhance the visibility of the number plate in each frame.
  3. Number Plate Detection: A Haar Cascade Classifier is used for number plate detection in each frame, which involves applying a pre-trained model to locate the plate's region.
  4. Text Recognition: EasyOCR is employed to recognize the text on the number plate in real-time.

Results
      You can view the real-time results, including recognized text, in the webcam feed.
