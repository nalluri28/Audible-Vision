Object Detection with voice output for the visually Impaired

Overview
This Python project utilizes the OpenCV library for object detection in real-time video
streams. It employs a pre-trained YOLO (You Only Look Once) model to detect various
objects within the video feed. Additionally, the project includes a voice output feature to
announce the detected objects and their locations within the frame. The primary aim of this
project is to aid visually impaired individuals by providing auditory cues about their
surroundings through a webcam feed.

Features
● Real-time object detection using YOLOv3 model.
● Voice output functionality to announce detected objects and their positions.
● User-friendly interface providing visual feedback alongside auditory cues.
● FPS (Frames Per Second) counter for performance monitoring.
● Flexible and configurable to accommodate various environments and user
preferences.

Requirements
● Python 3.x
● OpenCV (cv2)
● NumPy
● Pyttsx3
● Command prompt

Installation
1. Clone or download the project repository from GitHub.
2. Install the required Python libraries using pip:
pip install opencv-python numpy pyttsx3
3. Download the YOLOv3 weights, configuration file, and the COCO class labels file.
Ensure they are placed in the appropriate directories as specified in the code.

Usage
1. Run the Python script object_detection.py.
2. Ensure your webcam is connected and properly configured.
3. The script will open a window displaying the webcam feed with real-time object
detection annotations.
4. Detected objects will be announced verbally through your system's speakers or
headphones.
5. Press the 'Esc' key to exit the application.
6. 
Configuration
● Adjust the confidence threshold for object detection by modifying the
confidence_threshold variable in the code.
● Customize the YOLO model weights, configuration file, and class labels file paths
according to your setup.
● Fine-tune the object detection parameters such as Non-Maximum Suppression (NMS)
threshold for improved performance.

Acknowledgments
● The project utilizes the YOLO object detection model and is built upon the
foundations of OpenCV and Python.
● Special thanks to the OpenCV community for their contributions and support in
developing computer vision applications
