# ADAPTIVE-TRAFFIC-SYSTEM-
The purpose of this project is to detect and track vehicles on a video stream and count those going through a defined line.

highway.gif

It uses:

YOLO to detect objects on each of the video frames.

SORT to track those objects over different frames.

Once the objects are detected and tracked over different frames a simple mathematical calculation is applied to count the intersections between the vehicles previous and current frame positions with a defined line.

The code on this prototype uses the code structure developed by Adrian Rosebrock for his article YOLO object detection with OpenCV.
