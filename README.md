# Gun Detection using OpenCV

This project utilizes OpenCV, an open-source computer vision library, to detect guns from a camera feed in real-time.

## Overview

The aim of this project is to develop a system capable of identifying firearms in a live video stream. It employs a pre-trained Haar cascade classifier to detect guns within the frames captured by the camera.

## Requirements

- Python 3.x
- OpenCV library
- Numpy
- Imutils

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Nikhilbhardwaj13/opencv-gun-detection.git

Ensure you have Python installed on your system.
Install the required Python libraries:

pip install opencv-python numpy imutils

Usage
1.Navigate to the project directory:
cd opencv-gun-detection
2.Run the main script:
python gun_detection.py
3.The script will access your camera feed and display the video stream. If a gun is detected, it will be highlighted within the frame with a bounding box.
4.Press 'q' to exit the application.

File Structure
1.gun_detection.py: The main Python script containing the gun detection algorithm.
2.cascade.xml: Pre-trained Haar cascade classifier for gun detection.
3.README.md: This file, providing an overview of the project, installation instructions, and usage guidelines.

Credits
The gun detection algorithm is based on the work of the OpenCV community.
Special thanks to the authors of the cascade.xml file used for training the gun classifier.

Disclaimer
This project is developed for educational purposes only. The detection accuracy may vary depending on environmental conditions, camera quality, and other factors. It is not intended for use in high-stakes security applications
