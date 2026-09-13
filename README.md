Computer Vision & Deep Learning PR-3

Project Overview

This project is a practical Computer Vision and Deep Learning project
completed using Python, OpenCV, NumPy, Matplotlib, YuNet and YOLOv8.

Here is my Explanation Video Link : https://drive.google.com/drive/folders/11JuUEkoyRLiX7bQwp_LoWRHadeYHttzR?usp=sharing



Outputs:

<img width="681" height="514" alt="Screenshot 2026-09-13 131416" src="https://github.com/user-attachments/assets/400cc5c4-939d-4618-b7ff-380dbb4c26f3" />
          <img width="644" height="524" alt="Screenshot 2026-09-13 132507" src="https://github.com/user-attachments/assets/e2c4e2c8-b8a3-415b-bc03-c5d5bb7a679c" />
          <img width="654" height="507" alt="Screenshot 2026-09-13 133157" src="https://github.com/user-attachments/assets/3ece0718-5820-4dcb-9403-bdc4e5abc003" />
  

The main objective of the project is to understand image processing,
face detection, object detection and real-time computer vision
pipelines.

Technologies Used

Python 3

OpenCV

NumPy

Matplotlib

YuNet Face Detection

YOLOv8n

Jupyter Notebook

Project Tasks

1. Morphological Operations

In this part, different classical image processing techniques were
performed:

Grayscale conversion

Binary thresholding

Erosion

Dilation

Opening

Closing

Kernel shape and size comparison

Morphological operations were used to understand how image regions can
be cleaned, expanded and modified.

2. Bitwise Operations & Histograms

Two binary masks were created and different bitwise operations were
applied:

AND

OR

XOR

NOT

A masked region of an image was also extracted.

Image histograms were generated for:

Grayscale

Blue channel

Green channel

Red channel

Brightness and contrast were also adjusted using alpha and beta values.

3. Face Detection using YuNet

YuNet was used for face detection on images and webcam frames.

The detector displays:

Face bounding box

Confidence score

Five facial landmarks

Different confidence thresholds were also tested to understand the
effect of detection sensitivity.

4. Object Detection using YOLOv8

A pretrained YOLOv8n model was used for object detection.

YOLOv8 was tested on static images and webcam frames. The output
contains:

Bounding boxes

Object class names

Confidence scores

Confidence thresholds and IoU thresholds were also tested.

A per-class detection summary and bar chart were created to understand
the detected object distribution.

5. Integrated Pipeline & Final Comparison

The final pipeline combines YuNet and YOLOv8 on the same webcam
stream.

YuNet detects faces using green bounding boxes.

YOLOv8 detects general objects and displays their class labels.

Both detection layers are shown on the same output frame.

Morphological opening was also tested as optional preprocessing.

FPS was benchmarked for:

YuNet only

YOLOv8 only

Combined YuNet + YOLOv8

Project Results

YuNet Face Detection

YuNet successfully detected a face and displayed the confidence score
and five facial landmarks.



YOLOv8 Webcam Detection

YOLOv8 successfully detected a person and a mobile phone in the webcam
frame.



Combined YuNet + YOLOv8

The integrated pipeline successfully detected both a face and general
objects in the same webcam frame.

In the example below:

Green box represents YuNet face detection.

YOLO bounding boxes and labels represent object detection.



Key Learning

Through this project, I learned how classical computer vision techniques
and deep learning models can be combined in a real-time computer vision
application.

The project also helped me understand the trade-off between accuracy,
confidence threshold, preprocessing and processing speed (FPS).

Conclusion

This project demonstrates a complete computer vision workflow, starting
from basic image processing and moving towards deep learning-based face
and object detection.

The integrated YuNet + YOLOv8 pipeline shows how different models can
work together for real-time monitoring and detection applications.

Author

Purvi Talaviya
