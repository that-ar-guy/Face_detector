# Real-Time Face Detection System using OpenCV

This project is a real-time face detection system implemented in Python using the OpenCV library. It captures video frames from a webcam and detects faces in each frame using a pre-trained Haar Cascade classifier.

## Features:

- **Real-Time Detection:** The application captures video frames from the webcam and detects faces in each frame in real-time.
- **OpenCV Integration:** Utilizes the OpenCV library, a powerful computer vision library, for handling video input and performing face detection.
- **Haar Cascade Classifier:** The project uses a pre-trained Haar Cascade classifier (`haarcascade_frontalface_default.xml`) provided by OpenCV for detecting frontal faces in images.
- **Bounding Box Visualization:** Detected faces are highlighted using bounding boxes drawn around them, making them visually distinguishable from the rest of the image.
- **User Interaction:** The application runs in a while loop until the user presses the 'S' key, upon which the application terminates, releasing the webcam resources.

## Usage:

1. **Installation:**
   - Ensure you have Python installed on your system.
   - Install the required libraries using the following command:
     ```
     pip install opencv-python
     ```

2. **Running the Application:**
   - Run the Python script (`face_detection.py`) to launch the face detection application.
   - The webcam feed will open in a window with real-time face detection overlaid.
   - Press the 'S' key to exit the application.

## Files:

- **face_detection.py:** Main Python script that implements the real-time face detection system using OpenCV.
- **haarcascade_frontalface_default.xml:** Pre-trained Haar Cascade classifier for detecting frontal faces in images.

## Contribution:

Contributions to the project are welcome. You can contribute by submitting bug reports, feature requests, or pull requests to improve the functionality and usability of the application.
