🚦 Traffic Sign Recognition Using CNN
📌 Project Overview

This project implements a Traffic Sign Recognition System using a Convolutional Neural Network (CNN).
The model is trained to accurately classify traffic sign images into their respective categories, which is a crucial component of Advanced Driver Assistance Systems (ADAS) and autonomous vehicles.

🎯 Objectives

To preprocess and analyze traffic sign image data

To build and train a CNN-based deep learning model

To evaluate model performance using accuracy and loss metrics

To demonstrate the effectiveness of CNNs in image classification tasks

🧠 Technologies Used

Programming Language: Python

Libraries & Frameworks:

TensorFlow / Keras

NumPy

Pandas

Matplotlib

OpenCV

Platform: Jupyter Notebook

📂 Project Structure
├── CNN_Traffic_Signs.ipynb
├── dataset/
│   ├── Train/
│   └── Test/
├── README.md

🔄 Workflow

Dataset Loading
Traffic sign images are loaded from the dataset directory.

Image Preprocessing

Resizing images

Normalization

Label encoding

Model Building

Convolutional layers

Max pooling layers

Fully connected (Dense) layers

Softmax output layer

Model Training

Optimizer: Adam

Loss Function: Categorical Crossentropy

Model Evaluation

Accuracy and loss visualization

Prediction on test data

📊 Results

Achieved high accuracy on the test dataset

The CNN model successfully learned traffic sign features such as shapes and symbols
