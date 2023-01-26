# Face-Mask-Detection

## Problem Statement
India has been fighting the COVID-19 pandemic since 30 January 2020 when the first case of COVID-19 was reported.  
With the Unlock 4.0 phase set to begin in September, the need to be proactive is now more than ever. 
The objective is to create a Real-Time Face Mask Detector which can solve monitoring issues in crowded areas such as Airports, Metros, etc. using CNN and OpenCV.
## Dataset Description
The dataset is an artificial set of face mask images
* Total Images: 1376
  * with_mask images: 
  * without_mask images: 
* The goal is to create a Deep Learning model to detect in real-time whether a person is wearing a face mask or not

## Model Building
* Import Required Libraries
* Load and Preprocess the dataset
* Split the dataset
* Create Training and Validation Data Generators using Keras ImageDataGenerator function
* Encode the categorical data
* Visualize Images
* Build Basic CNN Model and also build a model using MobileNetV2 (transfer learning)
  * Compile the model
  * Fit the model
  * Check accuracy,val_accuracy,loss,val_loss
  * Predict new images
* Using OpenCV detect face mask of people in a video using model build
