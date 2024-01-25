# face_and_skin_detection

This Python program utilizes the OpenCV library for face detection and skin detection in an image. The program reads an image, detects faces using Haar cascades, and then applies a skin detection algorithm based on RGB thresholding.

Prerequisites

Make sure you have the required libraries installed before running the program:

OpenCV (cv2)
NumPy (numpy)
Matplotlib (matplotlib)
Google Colab patches (google.colab.patches)
SciPy (scipy)

Description

The program starts by reading an image (familyFun.jpg in this case) and loading a Haar cascade classifier for face detection.
It then applies face detection to the image and draws rectangles around the detected faces.
The program also includes commented-out code for extracting and displaying the detected faces.
Following the face detection, the original image is passed through a skin detector using an RGB thresholding approach.
The skin-detected image is displayed, and additional processing steps, such as median blurring, are applied to enhance the results.
