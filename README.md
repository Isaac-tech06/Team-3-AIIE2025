# Team-3-AIIE2025

* Cars vs Motorcycles
* Justin - Carl - Isaac

# Problem Statement
* To develop a convolutional neural network (CNN)-based image classification model which can accurately distinguish between images of cars and motorcyles. 

# Dataset
* Url: https://www.kaggle.com/datasets/kaggleashwin/vehicle-type-recognition

## Description : 
* The dataset is organized into four classes, each representing a different type of vehicle:

* Car: Images of different car models and types, captured from various angles and under different lighting conditions.

* Motorcycle: Images of motorcycles and motorbikes.

## Number of images in the dataset : 200
* Car : 100 images
* Motorcicle : 100 images

## Model
* CNN (Convolutional Neural Network) - Deep learning model specialized for image processing. This model is designed for automatic learning of features such as edges, shapes, and image textures. 

* Input - Images

* The CNN models applies filters/kernels to the inputted image in order to extract features. This results in the creation of multiple feature maps which are then flattened and fed through dense layers. Finally, the model outputs a set of scores which represents the model's choice of classification. 

## Image Processing
* Our Vehicle Type Recognition dataset featured four folders (Bus, Car, Truck, motorcycle) each with 100 images (total of 400 files in our dataset).

* The Car and motorcycle folders were moved to a separate "test" and "train" directory where we split the photos accordingly for each trial.

* The splits used for this experiment include:
80 : 20 = 80% (160 files) for training and 20% (40 files) for testing
70 : 30 = 70% (140 files) for training and 30% (60 files) for testing
60 : 40 = 60% (120 files) for training and 40% (80 files) for testing
50 : 50 = 50% (100 files) for training and 50% (50 files) for testing
85 : 15 = 85% (175 files) for training and 15% (30 files) for 

* Since CNNs require a fixed input size for inputted images, we decided to test out three different image sizes to be fed into the model. These sizes include 150 x 150, 128 x 128 ,and 224 x 224. 
