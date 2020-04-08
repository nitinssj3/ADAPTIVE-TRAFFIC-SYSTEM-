# ADAPTIVE-TRAFFIC-SYSTEM-
The purpose of this project is to detect and track vehicles on a video stream and count those going through a defined line.



It uses:

YOLO to detect objects on each of the video frames.

SORT to track those objects over different frames.

Once the objects are detected and tracked over different frames a simple mathematical calculation is applied to count the intersections between the vehicles previous and current frame positions with a defined line.

The code on this prototype uses the code structure developed by Adrian Rosebrock for his article YOLO object detection with OpenCV.

STEPS
Download the code to your computer.
Download yolov3.weights(https://www.dropbox.com/s/99mm7olr1ohtjbq/yolov3.weights?dl=0) and place it in /yolo-coco.
Make sure you have Python 3.7.0 and OpenCV 3.4.2 installed.
Run:
