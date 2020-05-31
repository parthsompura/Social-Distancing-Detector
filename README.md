# Social Distancing Detector   [![](https://img.shields.io/github/license/sourcerer-io/hall-of-fame.svg?colorB=ff0000)](https://github.com/ParthPathak27/Social-Distancing-Detector/blob/master/LICENSE)  [![](https://img.shields.io/badge/Parth-Pathak-brightgreen.svg?colorB=ff0000)](https://www.linkedin.com/in/parth-pathak-learner/)
An AI Tool to Help Customers Monitor Social Distancing in the Workplace.

### Sourcerer [![](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Social-Distancing-Detector/images/0)](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Social-Distancing-Detector/links/0)[![](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Social-Distancing-Detector/images/1)](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Social-Distancing-Detector/links/1)[![](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Social-Distancing-Detector/images/2)](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Social-Distancing-Detector/links/2)[![](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Social-Distancing-Detector/images/3)](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Social-Distancing-Detector/links/3)[![](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Social-Distancing-Detector/images/4)](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Social-Distancing-Detector/links/4)[![](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Social-Distancing-Detector/images/5)](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Social-Distancing-Detector/links/5)[![](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Social-Distancing-Detector/images/6)](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Social-Distancing-Detector/links/6)[![](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Social-Distancing-Detector/images/7)](https://sourcerer.io/fame/ParthPathak27/ParthPathak27/Social-Distancing-Detector/links/7)

In the fight against the coronavirus, social distancing has proven to be a very effective measure to slow down the spread of the disease. While millions of people are staying at home to help flatten the curve, many customers in the manufacturing and pharmaceutical industries are still having to go to work everyday to make sure our basic needs are met.

To help ensure social distancing protocol in their workplace, I have developed an AI-enabled social distancing detection tool that can detect if people are keeping a safe distance from each other by analyzing real time video streams from the camera.

The demos below will help to visually explain the approach that consists of three main steps:

1. Detect the humans in the frame with yolov3 convolutional neural network.
2. Calculate the distance between all the instances of humans detected in the frame.
3. Classify the determined distances as 'Alert' or 'Ok' for social distancing.

### Output (Image)
![screenshot](https://github.com/ParthPathak27/Social-Distancing-Detector/blob/master/output.jpg)

### Output (Video)
This demo video is performed on the public “OXFORD TOWN CENTRE” dataset

![This demo video is performed on the public “OXFORD TOWN CENTRE” dataset](https://github.com/ParthPathak27/Social-Distancing-Detector/blob/master/output.gif)


### Requirements:

1. Numpy
2. Time
3. OpenCV
4. OpenCV_Contrib
5. Math

Download yolov3.weights for COCO dataset from this link and add it to your repo, [click here](https://pjreddie.com/darknet/yolo/)

### Installation of Model:

* To deploy algorithm on images, python SDD_Image.py
* To deploy algorithm on videos, python SDD_Video.py
* To deploy algorithm on live streaming webcam, python SDD_Camera.py


Reference: https://landing.ai/landing-ai-creates-an-ai-tool-to-help-customers-monitor-social-distancing-in-the-workplace/
