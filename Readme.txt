
Train YOLO to Detect Custom Objects
==================================

Group Members:   Mahrang Saeed, Haoyuan Wang, Xunan Dai

Files:
1. Presentation slides: Train YOLO to Detect Custom Objects.pdf
2. CMPE297 Final Report.pdf
3. Source code: https://github.com/AlexeyAB/darknet

Requirements on Windows/Linux
=============
    1) CMake >= 3.8 for modern CUDA support
    2) CUDA 10.0
    3) OpenCV >= 2.4
    4) cuDNN >= 7.0 for CUDA 10.0 
    5) GPU with CC >= 3.0
    6) on Linux GCC or Clang, on Windows MSVC 2015/2017/2019

Download Darknet Framework
================

https://github.com/AlexeyAB/darknet

To start training: 
./darknet detector train cfg/obj.data cfg/yolo-obj.cfg darknet19_448.conv.23

Demos
=====

Please see attached presentation slides.

Acknowledgements
================

Step by step instruction is from: 
https://timebutt.github.io/static/how-to-train-yolov2-to-detect-custom-objects/


