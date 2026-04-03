# Chest X-ray Pneumonia Classification using CNN

# Objective
The objective of this project is to develop a Convolutional Neural Network (CNN) model that can classify chest X-ray images into two categories:Pneumonia and Normal.  
This model aims to assist in the early detection of pneumonia using medical images.
# Dataset
The dataset consists of X-ray images categorized into two classes:
- Pneumonia
- Normal
The dataset is organized into three directories:
train — used for training
val— used for validation  
test — used for testing  
# Methodology

# Preprocessing
- Images were resized to 150 × 150 pixels  
- Pixel values were normalized (rescaled from 0–255 to 0–1)
# Model
A CNN model was used for image classification consisting of:
- Conv2D layers  
- MaxPooling layers  
- Flatten layer  
- Dense layer  
- Sigmoid output layer (Binary Classification)
# Training
- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Training Dataset:Train set
- Validation Dataset:Validation set

# Results
The model achieved:
Test Accuracy: 76.44%  
Test Loss: 2.0391
