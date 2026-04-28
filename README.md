## Car Detection using OpenCV

**Description**

This project detects cars in a video using OpenCV and a Haar Cascade classifier (cars.xml).

Each frame is processed, and detected vehicles are highlighted with bounding boxes in real time.


**How It Works**

Load Haar Cascade model

Read video frame by frame

Convert to grayscale

Detect cars using detectMultiScale()

Draw rectangles around detected cars

**Usage**

python car_detection.py

**Result**

Cars are detected in the video

Bounding boxes are drawn around vehicles

Output is displayed in a real-time window
