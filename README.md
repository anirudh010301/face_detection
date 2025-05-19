Face Detection using OpenCV
This project implements a simple real-time face detection application using OpenCV and Haar Cascade classifiers.

Features
Detects faces from a webcam video stream

Draws rectangles around detected faces

Uses the haarcascade_frontalface_default.xml Haar cascade classifier

Requirements
Python 3.x

OpenCV (cv2)

Installation
1) Clone this repository:

bash
git clone https://github.com/yourusername/face-detection-opencv.git
cd face-detection-opencv


2) Install dependencies:

bash

pip install opencv-python


3) Make sure the haarcascade_frontalface_default.xml file is in the same directory as main.py.

Usage
Run the script:

bash
Copy
Edit
python main.py
This will open your webcam and start detecting faces. Press q to exit.

File Structure
bash
Copy
Edit
.
├── main.py                        # Main script for face detection
└── haarcascade_frontalface_default.xml  # Haar cascade classifier for face detection














License
This project is licensed under the MIT License.

