# Facial-Emotion-Detection
Detecting the Emotion using Convolutional Neural Network and OpenCV

# Project Overview
This project implements a Facial Emotion Recognition system using a Convolutional Neural Network (CNN) trained on the FER2013 dataset. The model classifies facial expressions into seven categories:
1. Angry
2. Disgust
3. Fear
4. Happy
5. Neutral
6. Sad
7. Surprise


# Tech Stack
. Python

. TensorFlow/Keras (Deep Learning Framework)

. OpenCV (Image Processing)

. NumPy & Pandas (Data Handling)

. Matplotlib (Data Visualization)

* Dataset: FER2013(From Kaggle)
The FER2013 dataset contains 48x48 grayscale images of facial expressions. 

It is available in CSV format, where each row consists of:
* Emotion Label (0-6)
* Pixel Values (Space-separated string of 48x48 = 2304 values)

📌 Installation

1. Install Dependencies
* pip install tensorflow numpy pandas opencv-python matplotlib scikit-learn 

2. Training the Model
Run the following script to train the CNN model:
* python train.py

3. Uses OpenCV to capture video frames.

4. To run your real-time emotion detection script, execute the following command in your terminal:
* python real_time_emotion.py

