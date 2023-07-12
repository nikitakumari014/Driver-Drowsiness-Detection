# Driver-Drowsiness-Detection

## Description
The Driver Drowsiness Detection System is a model built using Keras, TensorFlow, and Computer Vision techniques. The purpose of this system is to detect if a driver is in an exhausted state while operating a vehicle. It utilizes a combination of facial landmarks detection, eye tracking, and machine learning algorithms to monitor the driver's eyes and alert them if signs of drowsiness are detected.

The Driver Drowsiness Detection System is a model built using two different approaches:
### Approach 1: Deep Learning with TensorFlow and Keras
In this approach, I built a deep-learning model using TensorFlow and Keras. The model utilizes Convolutional Neural Networks (CNNs) to analyze facial features and detect signs of drowsiness. By training the model on a large dataset of labeled images, it learns to recognize specific patterns and features associated with drowsy states. This approach achieved an accuracy of 90% in identifying drowsiness.

### Approach 2: Computer Vision with dlib Library
The second approach leverages the dlib library, which provides a comprehensive set of computer vision algorithms and tools. I used dlib to perform facial landmarks detection and eye tracking. By tracking the movement and behavior of the driver's eyes, I could identify signs of drowsiness, such as prolonged eye closure or heavy blinking. This approach achieved an accuracy of 94.46% in identifying drowsiness.

By combining both approaches, I aim to improve the overall accuracy and robustness of the driver drowsiness detection system.


## Features
- Approach 1: Deep learning model using TensorFlow and Keras
- Approach 2: Computer vision techniques with dlib library
- Detects drowsiness based on facial features and eye tracking
- Achieves high accuracy in identifying drowsy states

## Requirements
- Python (version 3.11.4)
- TensorFlow (version 2.13.0)
- Keras (version 3.7.2)
- OpenCV (version 4.7.0)
- dlib (version 19.24.2)

## Installation
1. git clone https://github.com/nikitakumari014/Driver-Drowsiness-Detection.git
2. Install the required dependencies

## Usage
1. Run the main script to start the driver drowsiness detection system: python file_name.py
2. The system will use the camera feed to track the driver's eyes and analyze their state.
3. If drowsiness is detected, an alert will be triggered to notify the driver.

## Dataset
Click [here](http://mrl.cs.vsb.cz/eyedataset) to access the dataset download page.
