# CodeAlpha_Object_Detection_Tracking
# CodeAlpha - Object Detection and Tracking

## Description

This project implements an Object Detection and Tracking system using Computer Vision techniques. It utilizes the YOLOv8 pre-trained model for detecting objects in video streams and OpenCV for video processing. The system identifies objects, draws bounding boxes around them, and tracks their movement across frames using object tracking algorithms.

## Features

* Real-time object detection from video input
* Object classification using YOLOv8
* Bounding box visualization
* Multi-object tracking with tracking IDs
* Video frame processing using OpenCV
* Automated object monitoring across frames

## Technologies Used

* Python
* OpenCV
* YOLOv8 (Ultralytics)
* Computer Vision
* Google Colab

## Workflow

1. Load a video file or webcam stream.
2. Process video frames using OpenCV.
3. Apply YOLOv8 for object detection.
4. Detect and classify objects in each frame.
5. Draw bounding boxes and labels around detected objects.
6. Track detected objects across consecutive frames.
7. Display the processed output with object labels and tracking IDs.

## Project Structure

CodeAlpha_Object_Detection_Tracking/
│
├── Task4_Object_Detection_Tracking.ipynb
├── output.mp4
├── README.md

## Applications

* Smart Surveillance Systems
* Traffic Monitoring
* Autonomous Vehicles
* Security and Safety Analytics
* Retail and Crowd Monitoring

## Outcome

The system successfully detects and tracks multiple objects in a video stream, displaying bounding boxes, object labels, and tracking IDs in real time.

## Future Enhancements

* Deep SORT Integration
* Live Webcam Detection
* Custom Object Training
* Real-Time Alert Generation
* Cloud-Based Video Analytics
