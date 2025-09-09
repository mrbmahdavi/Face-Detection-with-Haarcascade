# Face-Detection-with-Haarcascade
Detecting faces in an image using a pre-trained haar cascade model

## Table of contents
-[Overview](#Overview)
-[Features](#Features)
-[Requirements](#Requirements)
-[Usage](#Usage)
-[Results](#Results)
-[Notes](#Notes)

## 📖 Overview
This project implements face detection in images using **OpenCV's Haar Cascade classifier**. It demonstrates how to detect and extract faces from an image, draw bounding boxes around detected faces, and display the results.

## ✨ Features
* Load and process images for face detection
* Utilize pre-trained Haar Cascade model for face detection
* Detect multiple faces in a single image
* Extract and display individual detected faces
* Draw bounding boxes around detected faces in the original image
* Display both the original image with bounding boxes and individual face crops

## 📋 Requirements
* Python 3.x

*  OpenCV (cv2) library

* haarcascade_frontalface_default.xml (OpenCV's pre-trained Haar Cascade model)

## 🚀 Usage
1. Place your image file in the project directory (default: 'gold.png') 📂

2. Update the image filename in the code if needed 

3. Run the Jupyter notebook or Python script ▶️

4. The program will:

- Detect faces in the image

- Display each detected face in a separate window

- Show the original image with bounding boxes around detected faces

- Print the number of faces detected

## 📊 Results
The program outputs:

* The number of faces detected in the image

* Separate windows showing each detected face

* The original image with green bounding boxes around all detected faces

## 💡 Notes
- Press any key to close the image windows after execution

- The Haar Cascade classifier is effective for frontal face detection but may have limitations with profile faces or under varying lighting conditions

- Adjust parameters in detectMultiScale for better results with different images

