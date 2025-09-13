YOLOv3 Real-Time Object Detection

This project demonstrates real-time object detection using the YOLOv3 (You Only Look Once) algorithm with OpenCV’s Deep Neural Network (DNN) module. It can detect multiple objects in images, videos, or a live webcam feed with bounding boxes and labels.

📂 Files Included

data (2).py – Main Python script for object detection.

yolo.cfg – YOLOv3 network configuration file.

yolov3.weights – Pre-trained YOLOv3 weights.

coco.names – Class labels for 80 common objects.

🚀 Features

Detects objects in videos, images, or live webcam feeds.

Displays FPS and timestamps for frames.

Uses Non-Maximum Suppression (NMS) to reduce overlapping boxes.

Randomized colors for bounding boxes for better visualization.

🛠 Requirements

Python 3.x

OpenCV (pip install opencv-python)

NumPy (pip install numpy)

▶ Usage

Clone the repository and place all files in the same folder.

Run the script:

python data\ \(2\).py


Enter a video filename or type live_feed to use your webcam.

Press q to exit.

📌 Credits

YOLOv3: Joseph Redmon et al.

Pre-trained weights and configuration: Darknet YOLO
