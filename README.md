# Real Time Face Mask Detection
Face Mask Detection System built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in real-time video streams.

## Purpose
COVID-19 pandemic has taken the world by surprise and there is a high need for efficient face mask detection applications for transportation means, densely populated areas, residential districts, large-scale manufacturers and other enterprises to ensure safety. The sole purpose of this application is to ease this process and make a fully automatic face-mask detection application.

## Demo
![Demo](demo.gif)

## Tech Used
* OpenCV
* Caffe-based face detector
* Tensorflow and Keras
* MobileNetV2

## Installation
To install the dependencies:<br>
```bash
pip install -r requirements.txt
```

## Working
To train the model:<br>
```bash
python train_model.py
```

Alternatively, you can also use the already trained model present in the folder.<br>

To detect face masks in real-time:
```bash
python detect_face.py
```





