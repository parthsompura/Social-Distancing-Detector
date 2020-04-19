# Social Distancing Detector
An AI Tool to Help Customers Monitor Social Distancing in the Workplace4

1. Detect the humans in the frame with yolov3 convolutional neural network.
2. Calculate the distance between all the instances of humans detected in the frame.
3. Classify the determined distances as 'Alert' or 'Ok' for social distancing.

# Output (Image)
![screenshot](https://github.com/ParthPathak27/Social-Distancing-Detector/blob/master/output.jpg)

# Output (Video)
![This demo video is performed on the public “OXFORD TOWN CENTRE” dataset](https://github.com/ParthPathak27/Social-Distancing-Detector/blob/master/output.gif)

# Requirements:

1. Numpy
2. OpenCV
3. OpenCV_Contrib
4. Math
5. Time

Download yolov3.weights for COCO dataset from this link and add it to your repo, [click here](https://pjreddie.com/darknet/yolo/)

# Installation of Model:

* To deploy algorithm on images, python SDD_Image.py
* To deploy algorithm on videos, python SDD_Video.py
* To deploy algorithm on live streaming webcam, python SDD_Camera.py

# Reference:

https://landing.ai/landing-ai-creates-an-ai-tool-to-help-customers-monitor-social-distancing-in-the-workplace/
