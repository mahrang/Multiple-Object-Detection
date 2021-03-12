Group Members:   Mahrang Saeed, Haoyuan Wang, Xunan Dai

To train YOLOv3 on COCO dataset:
================================

Visit https://pjreddie.com/darknet/yolo/
Scroll down to "Detection Using A Pre-Trained Model" and run the commands to install Darknet.
Scroll down to "Training YOLO on COCO" and run the commands to train YOLOv3 model on COCO dataset.
Scroll up to "Real-Time Detection on a Webcam" and run the commands to detect objects from webcam or video file.

You may also use the Python code provided in our Code folder to use YOLOv3 trained on COCO to perform detection on images/videos.

After training YOLOv3 on COCO dataset, we processed a video file by YOLOv3 to detect objects in an autonomous driving scenario.
Here is the output video annotated with bounding boxes and class names:  https://www.youtube.com/watch?v=U4y2hvrecSw

Annotated still frames from the video can be seen in the folder "Stills From YOLOv3 COCO Video".


To Train YOLOv3 to Detect Custom Objects:
=========================================

Step by step instructions are provided at: 
https://manivannan-ai.medium.com/how-to-train-yolov3-to-detect-custom-objects-ccbcafeb13d2
https://timebutt.github.io/static/how-to-train-yolov2-to-detect-custom-objects/

Download Darknet Framework at:
https://github.com/AlexeyAB/darknet

To start training YOLOv3 model on a dataset, run the following command: 
./darknet detector train cfg/obj.data cfg/yolov3.cfg darknet53.conv.74

Requirements on Windows/Linux:
==============================
    1) CMake >= 3.8 for modern CUDA support
    2) CUDA 10.0
    3) OpenCV >= 2.4
    4) cuDNN >= 7.0 for CUDA 10.0 
    5) GPU with CC >= 3.0
    6) on Linux GCC or Clang, on Windows MSVC 2015/2017/2019

Files:
1. Our presentation slides: Train YOLO to Detect Custom Objects.pdf
2. CMPE297 Final Report.pdf
3. Doors Detected folder
4. Project YOLO.pdf
5. Code folder
6. Source code: https://github.com/AlexeyAB/darknet
7. YOLOv3 Paper.pdf
8. Stills From YOLOv3 COCO Video folder

See file #s 1-4 for our implementation of YOLOv3 to detect doors.
