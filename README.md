# Gesture-controlled-keyboard-mouse

# Read documentation [here](https://docs.google.com/document/d/1aSa_Mv0raawaPSm4AwRGtHYQ7T6YZIL5VXjRaFWbxGI/edit?usp=sharing)

# Overview
Gesture based keyboard and mouse is a Python scripted program that will identify gestures and allow the user to control mouse pointer and keyboard functions using hand gestures.
<br/>This project was created using OpenCV, MediaPipe, mouse, keyboard and wx libraries. We use color recognition and segmentation techniques to draw shapes on the whiteboard. We have used MediaPipeHands to identify the various pre - defined hand gestures that will be used to control the mouse pointer and use few keyboard commands.
<br/>OpenCV (Open Source Computer Vision Library) is an open source computer vision and machine learning software library. OpenCV was built to provide a common infrastructure for computer vision applications and to accelerate the use of machine perception in the commercial products. Being a BSD-licensed product, OpenCV makes it easy for businesses to utilize and modify the code.
<br/>MediaPipeHands is a fidelity hand and finger tracking solution. Using Machine Learning (ML) to derive 21 3D landmarks of the hand from a single image. MediaPipe Hands uses an ML pipeline consisting of multiple models that work together. A palm detection model that works across images and returns an oriented hand bounding box. A landmark model of the hand that works in the cropped image area defined by the palm detector and returns the key points of a high fidelity 3D hand. 
<br/>wxPython’s Project Phoenix is the improved next-generation wxPython. This new implementation is focused on improving speed, maintainability and extensibility. It wraps the wxWidgets C++ toolkit and provides access to the user interface portions of the wxWidgets API, enabling Python applications to have a native GUI on Windows, Macs or Unix systems.
<br/>Keyboard library is used to take full control of your keyboard for hooking global events, registering hotkeys, simulating key presses and much more.
<br/>Mouse library is used to get full control of your mouse. Hook global events, register hotkeys, simulate mouse movement and clicks, and much more.

# Project Prerequisites
<br/>Python     -           3.8.8 
<br/>OpenCV    -         4.4
<br/>Numpy     -          1.20.1
<br/>MediaPipe  -       0.8.8.1
<br/>Time-		   1.0.0
<br/>Mouse-		   0.7.1
<br/>Keyboard-	   0.13.5
<br/>wxPython-  	   4.1.1
<br/>HandTrackingModule (provided with the main code)


# Steps to execute gesture controlled keyboard and mouse :
<br/>Import necessary packages.
<br/>Read frames from a webcam
<br/>Keep both the HandTrackingModule and main in the same directory
<br/>Show your hand in the webcam
<br/>Once the hand is detected use gestures to control system
<br/>Press ‘q’ to quit the program


# Available Gestures
<br/>Scrolling UP gesture
<br/>Scrolling Down Gesture
<br/>Backspace Button Gesture
<br/>Enter Button Gesture
<br/>Escape Button Gesture
<br/>Mouse Pointer Gesture










