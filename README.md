# Driver-Drowsiness-Detection-System
Drowsiness detection is a safety technology that can prevent accidents that are caused by drivers who fall asleep while driving. In this Python project, we have built a drowsy driver alert system that we can implement in numerous ways. The system which can differentiate normal eye blink and drowsiness which can prevent the driver from entering the state of sleepiness while driving.

Proposed Methodology - In this Python project, we will be using OpenCV for gathering the images from webcam and feed them into a Deep Learning model which will classify whether the person’s eyes are ‘Open’ or ‘Closed’. The approach we will be using for this Python project is as follows :

Step 1 – Take image as input from a camera.

Step 2 – Detect the face in the image and create a Region of Interest (ROI).

Step 3 – Detect the eyes from ROI and feed it to the classifier.

Step 4 – Classifier will categorize whether eyes are open or closed.

Step 5 – Calculate score to check whether the person is drowsy.

Sample Test Case -

![image](https://user-images.githubusercontent.com/66421185/180601639-bc57ab20-deb1-402b-a71a-2d53ac0a8bb5.png)

The Model Architecture - The model we used is built with Keras using Convolutional Neural Networks (CNN). A convolutional neural network is a special type of deep neural network which performs extremely well for image classification purposes. A CNN basically consists of an input layer, an output layer and a hidden layer which can have multiple numbers of layers. A convolution operation is performed on these layers using a filter that performs 2D matrix multiplication on the layer and filter.

Software Used - Python 3.6 -- OpenCV, TensorFlow, Keras, Pygame
