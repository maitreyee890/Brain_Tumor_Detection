# Brain_Tumor_Detection
Brain Tumor Detection using Deep Learning
Overview

This project focuses on detecting brain tumors from MRI images using deep learning techniques. A convolutional neural network (CNN) is trained to classify MRI scans into tumor and non-tumor categories, helping demonstrate how AI can assist in medical image analysis.

The project is implemented in Python using popular deep learning and image processing libraries.

Dataset

MRI brain scan images

Includes tumor and non-tumor classes

Images are preprocessed and resized before training

(Dataset source can be added here if public)

Technologies & Tools Used

Programming Language: Python

Libraries:

NumPy

Pandas

Matplotlib

OpenCV

TensorFlow / Keras

Model Type: Convolutional Neural Network (CNN)

Platform: Jupyter Notebook

Project Workflow

Data Loading

Load MRI images from dataset directories

Preprocessing

Image resizing

Normalization

Label encoding

Model Building

CNN architecture with convolution, pooling, and dense layers

Model Training

Train the network on labeled MRI images

Evaluation

Accuracy and loss visualization

Prediction

Classify new MRI scans as tumor or non-tumor

Results

The model successfully learns visual features from MRI images

Achieves good accuracy in distinguishing tumor vs non-tumor scans

Performance visualized using training and validation curves

(You can add exact accuracy if you want)

How to Run the Project

Clone the repository:

git clone https://github.com/maitreyee890/Brain_Tumor_Detection


Install dependencies:

pip install numpy pandas matplotlib opencv-python tensorflow


Open the notebook:

jupyter notebook Brain_Tumor.ipynb


Run all cells sequentially
