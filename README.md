# Forest_Fire_Detection_System_using_DL
Forest Fire Detection Using Deep Learning Project 
Project Overview
This project focuses on using deep learning techniques for forest fire detection. The implementation is done in a Jupyter Notebook and utilizes a wildfire dataset from Kaggle.

Key Components
Dataset:

Uses "The Wildfire Dataset" from Kaggle (version 2)

Contains two classes: "fire" and "nofire" images

Dataset is organized into train, validation, and test directories

Technical Implementation:

Uses TensorFlow/Keras for deep learning model development

Implements image data generators for preprocessing

Employs GPU acceleration (checks for GPU availability)

Visualizes dataset samples and class distribution

Model Architecture:

Builds a convolutional neural network (CNN) using:

Conv2D layers

MaxPooling2D layers

Dense layers with Dropout

Uses sequential model structure

Key Steps:

Data loading and exploration

Image preprocessing and augmentation

Model construction and training

Performance evaluation

Dataset Details
Number of classes: 2 ("fire" and "nofire")

Sample images show forest scenes with and without fire

Dataset path: /kaggle/input/the-wildfire-dataset/the_wildfire_dataset_2n_version/

Technical Requirements
Python deep learning stack (TensorFlow, Keras)

GPU acceleration recommended

Kaggle environment used for dataset access

The project demonstrates a complete pipeline for building a deep learning solution for forest fire detection from dataset acquisition to model implementation. The CNN model is designed to classify images as containing fire or not, which could be valuable for early wildfire detection systems
