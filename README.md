# OVERVIEW
- This Python script utilizes OpenCV's Haar Cascade Classifier to perform real-time face detection through a webcam. It detects faces in the video feed and highlights them with green rectangles.

# FEATURES
- Real-time face detection using a webcam.
- Draws a green rectangle around detected faces.
- Gracefully exits when the 'q' key is pressed.

# HOW IT WORKS
- The script loads a pre-trained Haar Cascade Classifier for frontal face detection.
- Captures video feed from the default webcam (use VideoCapture(1) for external webcams).
- Converts each frame to grayscale for better detection performance.
- Detects faces and draws rectangles around them.
- Continuously displays the video feed with detections.

## MORE FILE DETAILES
- haarcascade_frontalface_default.xml: The pre-trained Haar Cascade model is loaded from OpenCV's default dataset.
- cv2.VideoCapture(0): Captures video from the system's default webcam.
- cv2.imshow(): Displays the video feed with detected faces.
