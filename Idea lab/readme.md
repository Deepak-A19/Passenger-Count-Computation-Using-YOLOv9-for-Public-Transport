# YOLOv9 Project

This project demonstrates the use of YOLOv9 for video object detection. It includes scripts for loading the model, processing video frames, and tracking objects.

## Files

- `main.py`: Main script for running the object detection and tracking.
- `tracker.py`: Script for tracking detected objects.
- `coco.txt`: List of COCO dataset class names.
- `busfinal.mp4`: Example video file for detection.
- `yolov9.pt`: YOLOv9 model weights file.

## Requirements

- OpenCV
- Pandas
- cvzone
- numpy
- yolov9

## Usage

1. Place the YOLOv9 weights file in the project directory and rename it to `yolov9.pt`.
2. Run `main.py` to start the object detection and tracking.

```bash
python main.py
