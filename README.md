# face_recognition_OpenCV
# Face Detection with OpenCV and Python

This repository contains a Python script for detecting faces in an image using the OpenCV library. The script utilizes OpenCV's Haar Cascade classifier, a popular method for object detection.

## Project Description

Face detection is a computer technology that determines the locations and sizes of human faces in arbitrary (digital) images. It detects facial features and ignores anything else, such as buildings, trees, and bodies. 

### How It Works

The script employs a pre-trained Haar Cascade model provided by OpenCV to identify faces within images. Haar Cascades are machine learning based classifiers that calculate certain features like edges or line in images, which they then use to detect objects. In our case, these features are used to detect faces:

1. **Load the Haar Cascade Classifier**: The classifier `haarcascade_frontalface_alt.xml` is loaded into the script.
2. **Read the Input Image**: The script reads an image file where faces will be detected. This image can be changed as needed.
3. **Face Detection Execution**: Using the classifier, the script processes the image to detect faces. Each face detected is marked with a rectangle.
4. **Output**: The script saves a new image that highlights faces with rectangles.

## Running the Script

Execute the script with the following command:

```bash
python face_detection.py


## Setup and Execution

To run this script, ensure you have Python and OpenCV installed:

```bash
pip install opencv-python-headless
