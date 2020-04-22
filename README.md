# Face Detection with Python using OpenCV
 <img src="https://raw.githubusercontent.com/vaibhavhariaramani/FaceDetection/master/images/detected%20face.png" width="250"/> <img src="https://raw.githubusercontent.com/vaibhavhariaramani/FaceDetection/master/images/grey.png" width="250"/> <img src="https://raw.githubusercontent.com/vaibhavhariaramani/FaceDetection/master/images/test6.jpg" width="250"/> 


Face detection is a computer vision technology that helps to locate/visualize human faces in digital images. This technique is a specific use case of object detection technology that deals with detecting instances of semantic objects of a certain class (such as humans, buildings or cars) in digital images and videos. With the advent of technology, face detection has gained a lot of importance especially in fields like photography, security, and marketing.

## Objective
This is the repository linked to the tutorial with the same name. The idea is to introduce people to the concept of object detection in Python using the OpenCV library and how it can be utilized to perform tasks like Facial detection.

## We’ll cover face detection using :
* Haar Cascade Classifiers using OpenCV
* Histogram of Oriented Gradients using Dlib
* Convolutional Neural Networks using Dlib

## Blogpost
[Face Detection with Python using OpenCV](https://vaibhavhariramani.blogspot.com/2020/04/a-full-guide-to-face-detection.html)

## Installation
OpenCV-Python supports all the leading platforms like Mac OS, Linux, and Windows. It can be installed in either of the following ways:

**1. From pre-built binaries and source :**

Please refer to the detailed documentation here for Windows and here for Mac.

**2. [Unofficial pre-built OpenCV packages for Python](https://pypi.org/project/opencv-python/).**

Packages for standard desktop environments (Windows, macOS, almost any GNU/Linux distribution)

run ```pip install opencv-python``` if you need only the main modules
run ```pip install opencv-contrib-python``` if you need both main and contrib modules (check extra modules listing from [OpenCV documentation](https://docs.opencv.org/master/))

## Table Of Contents


* [Images and OpenCV](#images-and-opencv)
* [Basic Operations on Images](#basic-operation-on-images)
* [Face Detection](#face-detection)



### Images and OpenCV
In this section we will perform simple operations on images using OpenCV like opening images, drawing simple shapes on images and interacting with images through callbacks. This is necessary to create a foundation before we move towards the advanced stuff.

* [Imports and models path](https://vaibhavhariramani.blogspot.com/2020/04/a-full-guide-to-face-detection.html)
* [Open CV Using Jupyter notebooks](https://vaibhavhariramani.blogspot.com/2020/04/a-full-guide-to-face-detection.html)
* [OpenCV Using Python Scripts](https://vaibhavhariramani.blogspot.com/2020/04/a-full-guide-to-face-detection.html)
* [Savings images](https://vaibhavhariramani.blogspot.com/2020/04/a-full-guide-to-face-detection.html)

### Basic Operation on Images
In this section, we will learn how we can draw various shapes on an existing image to get a flavour of working with OpenCV.

* [loading a test image](https://vaibhavhariramani.blogspot.com/2020/04/a-full-guide-to-face-detection.html)

### Face Detection
Face detection is a technique that identifies or locates human faces in digital images. A typical example of face detection occurs when we take photographs through our smartphones, and it instantly detects faces in the picture. Face detection is different from Face recognition. Face detection detects merely the presence of faces in an image while facial recognition involves identifying whose face it is.


Face detection is performed by using classifiers. A classifier is essentially an algorithm that decides whether a given image is positive(face) or negative(not a face). A classifier needs to be trained on thousands of images with and without faces. Fortunately, OpenCV already has pre-trained face detection classifiers, which can readily be used in a program. The classifiers are:
Haar Classifier .

[Haar feature-based cascade classifiers](https://vaibhavhariramani.blogspot.com/2020/04/a-full-guide-to-face-detection.html)
* [1. 'Haar features' extraction](https://vaibhavhariramani.blogspot.com/2020/04/a-full-guide-to-face-detection.html)
* [2. 'Integral Images' concept](https://vaibhavhariramani.blogspot.com/2020/04/a-full-guide-to-face-detection.html)
* [3. Detect face on an image](https://vaibhavhariramani.blogspot.com/2020/04/a-full-guide-to-face-detection.html)
* [4. Using 'Cascade of Classifiers'](https://vaibhavhariramani.blogspot.com/2020/04/a-full-guide-to-face-detection.html)
[Face Detection with OpenCV-Python](https://vaibhavhariramani.blogspot.com/2020/04/a-full-guide-to-face-detection.html)
