# Real-time Face Recognition with Age, Gender, and Emotion Detection

This repository presents a real-time computer vision solution that integrates various models to detect a person's face, estimate their age, determine their gender, and recognize their emotion within a given frame.

## Methodology/Principles

The core methodology and principles behind this solution are as follows:

1. **Face Detection using Dlib**: We employ the Dlib library to detect the Region of Interest (ROI) containing the person's face within the frame.

2. **Age, Gender, and Emotion Classification**: The ROI is then passed through a pre-trained neural network model to classify the individual's age, gender, and emotion.

3. **Face Recognition**: Additionally, we have implemented the `face_recognition` version 1.2.3 module to recognize specific faces, such as those of Modi and Trump, within the frame.

## Dependencies

To utilize this solution, you will need the following dependencies:

* Tensorflow
* Keras
* OpenCV (Opencv)
* Imutils
* face_recognition

You can install these dependencies using the appropriate package manager for your environment.

## Pre-trained Models

For the Age and Gender Detection, you can download the pre-trained model from the following link:

[Pre-trained Age and Gender Detection Model](https://github.com/yu4u/age-gender-estimation/releases/download/v0.5/weights.28-3.73.hdf5)

Ensure that you have this model file accessible for the Age and Gender estimation to work properly.

## Result

The result of running this real-time Face Recognition system with Age, Gender, and Emotion detection can be visualized in the image below:

![Result](result.png)

This image showcases the capabilities of the system in action, where faces are detected, and age, gender, and emotion are estimated.
