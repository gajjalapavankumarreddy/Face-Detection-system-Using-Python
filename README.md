# Face Detection using OpenCV

This project creates a simple face detection system using Python and OpenCV. It can find faces in images or real-time video streams with the Haar Cascade Classifier.

## Features

* Detects faces from images or webcam feed.
* Uses the Haar Cascade classifier (`haarcascade_frontalface_default.xml`).
* Offers real-time detection with bounding boxes.
* Provides an easy-to-use and lightweight code structure.

## Requirements

* Python 3.x
* OpenCV (`pip install opencv-python`)

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/facedetection.git
   cd facedetection
   ```

2. Place the `haarcascade_frontalface_default.xml` file in the same directory or update its path in the code.

3. Run the script:

   ```bash
   python facedetection.py
   ```

4. Allow camera access for real-time detection.

## Example Output

* Faces will be highlighted with rectangles in the live camera feed.

## Future Enhancements

* Add smile and eye detection.
* Integrate deep learning-based face detection (DNN).
* Build a simple GUI for non-programmers.
