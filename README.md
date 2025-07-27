# Computer Vision - Real-time Object Recognition 

## Introduction
This project  focuses on building a real-time object recognition system designed to detect and classify common objects from a live camera feed. It's developed using Python, MediaPipe, and OpenCV. The main function of the project includes capturing video from a camera, processing each frame to detect objects, and then overlaying the detection results (bounding boxes and labels) onto the live video display.

### About the project

The primary objective of this project is to develop a computer vision application capable of identifying a small, predefined set of common objects (e.g., chair, phone) within real-time video streams. This system uses pre-trained models of MediaPipe for object detection and classification, complemented by OpenCV for camera access, video processing and display.

### Objectives

1. **Object Detection with MediaPipe:** The system  implements the MediaPipe library for detecting and recognizing objects (e.g., phone, chair etc.) in real-time from a camera feed. An interface is developed using OpenCV that captures video, processes frames, and displays the detected objects with visual annotations on-screen.

2. **Object Classification:** A pre-trained MediaPipe model is employed to classify the detected objects, ensuring that the recognized objects are clearly identified with corresponding labels displayed on the screen.

**Tools**
    
1. **MediaPipe:** It's selected for its pre-trained machine learning models specifically designed for various vision tasks, including object detection. MediaPipe provides a streamlined API for integrating ML models into real-time applications

2.**OpenCV (Open Source Computer Vision Library):** It is used for camera interaction (capturing video frames), image preprocessing (e.g., color conversion, flipping), and visualizing the detection results (drawing bounding boxes, labels, and displaying the video stream).

 

 
