# Face-Emotions-Age-Gender Detection 

![Demo](https://github.com/erfan3940/face-emotions-age-detection/blob/main/captured/Face%20Recognition%204_5_2025%206_13_58%20PM.png)

![dowload demo video](https://github.com/erfan3940/face-emotions-age-detection/blob/main/captured/Face%20Recognition%202025-04-05%2018-12-04.mp4)

A real-time system that detects faces and predicts **age**, **gender**, and **emotions** simultaneously using OpenCV, Haar Cascades, and custom deep-learning models in both persian and english.

## Features
✔ **Face Detection** - Haar Cascade for bounding box detection.
✔ **Multi-Task Prediction** - Estimates:
   - **Gender** (Male/Female)
   - **Age** (Age group/range)
   - **Emotions** (Happy, Sad, Angry, Surprise, Fear, Neutral) *(Disgust excluded due to low dataset samples)*
✔ **Optimized for RTX 1650** - Uses TensorFlow for accelerated inference.

## Technologies Used
- **Python 3.9**
- **OpenCV** (Haar Cascade for face detection)
- **TensorFlow/Keras** (Custom CNN inspired by *LittleVGG*)
- **Haar Cascade Model**: `haarcascade_frontalface_default.xml`
- **Dataset**: [FER2013](https://www.kaggle.com/datasets/msambare/fer2013) (emotion training)

## Model Weights Disclaimer
Pre-trained weights for the WideResNet (age/gender) are **not included** in this repository due to large file sizes. Contact me for access or train your own model using the FER2013 dataset.
