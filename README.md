# Face Detection using OpenCV and Python

## Overview
This project demonstrates real-time face detection using OpenCV in Python. It utilizes the Haar cascade classifier to detect faces in a video stream from the webcam and highlights them with a bounding box.

## Requirements
Make sure you have the following dependencies installed:

- Python 3.x
- OpenCV

## Installation
1. Install OpenCV using pip:
   ```bash
   pip install opencv-python
   ```
2. Download the Haar cascade file (`haarcascade_frontalface_default.xml`) from the OpenCV GitHub repository or ensure it is in the project directory.
   ```bash
    https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml
   ```

## Usage
1. Run the Python script:
   ```bash
   python face-reco.py
   ```
2. The webcam will open, and detected faces will be highlighted with green rectangles.
3. Press `Esc` to exit the program.

## Code Explanation
- Loads the Haar cascade classifier.
- Captures video from the webcam.
- Converts each frame to grayscale for efficient processing.
- Detects faces in the frame using `detectMultiScale()`.
- Draws bounding boxes around detected faces.
- Displays the processed frame in a window.
- Exits the program when the `Esc` key is pressed.

## License
This project is open-source and available for educational purposes.

## Acknowledgments
- OpenCV documentation and tutorials
- Haar cascade classifiers for object detection

