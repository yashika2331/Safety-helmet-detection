# Safety-helmet-detection


**Overview**

This project is aimed at developing a helmet detection system using computer vision and machine learning techniques. The system is designed to analyze images or video streams to detect the presence or absence of helmets on individuals. This can be particularly useful for enhancing safety in settings such as construction sites, factories, or motorcycle monitoring.

**Features**

Detect the presence of helmets in images or real-time video streams.
Utilizes computer vision and deep learning models for object detection.
Offers the ability to process and analyze images or video from various sources.
Provides visual feedback by drawing bounding boxes around detected helmets.

**Prerequisites**

Python (version 3.X)
Libraries: OpenCV, TensorFlow, Keras (or other deep learning framework)
Pre-trained object detection model (e.g., SSD, YOLO, Faster R-CNN).Here SSD model is used.
Webcam or camera for real-time detection
Dataset for training and validation (if applicable)

**Installation**
1.Clone this repository to your local machine:
2.Activate the environment 
3.Install Tensorflow
4.Clone Tensorflow Object Detection API 
 https://github.com/tensorflow/models
5.Compiling protocol buffers
https://drive.google.com/drive/u/0/folders/1DUaVmJK63hL-F3Wjex1ojwhSI26tMAT_
6.Install all dependencies from setup.py file from tensorflow(tf1) package
7.Download SSD Mobilenet Model and pre trained weights of mscoco datasets and test on videos 
https://drive.google.com/drive/u/0/folders/1uXjHpTiZZnVXzppomwsOxls38gRhyVjH
8.Download pretrained weights of helmet detection model and run on inference videos
https://drive.google.com/drive/u/0/folders/17XPL7pKDiKi4dIJujR8L_Roep1MEmfBr
