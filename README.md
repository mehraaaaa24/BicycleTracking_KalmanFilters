# Bicycle Tracking using Kalman Filters

## Overview
This project implements real-time bicycle tracking using Kalman Filters for accurate position estimation and noise reduction. It utilizes object detection, motion prediction, and trajectory smoothing to efficiently track a bicycle in video frames.

## Features
- Object detection for identifying bicycles
- Kalman Filter implementation for motion prediction and smoothing
- Handles noisy detections and occlusions
- Real-time tracking in video sequences

## Requirements
Ensure you have the following dependencies installed:
```bash
pip install opencv-python numpy matplotlib
```

## Installation
Clone the repository and navigate to the project folder:
```bash
git clone https://github.com/yourusername/BicycleTracking_KalmanFilters.git
cd BicycleTracking_KalmanFilters
```

## Usage
Run the main script to process a video and track bicycles:
```bash
python track_bicycle.py --input video.mp4
```

## Algorithm
1. Detect the bicycle in the initial frames.
2. Apply Kalman Filter for motion prediction.
3. Correct predictions with new detections.
4. Visualize the tracking output.

## Output
The processed video will display a bounding box tracking the bicycle along with predicted positions.


## Acknowledgments
Inspired by Kalman Filtering techniques for object tracking in computer vision.

