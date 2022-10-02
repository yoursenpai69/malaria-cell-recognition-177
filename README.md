# Deep Neural Network for Malaria Infected Cell Recognition

## AIM

To develop a deep neural network for Malaria infected cell recognition and to analyze the performance.

## Problem Statement and Dataset

Malaria is a deadly, infectious mosquito-borne disease caused by Plasmodium parasites. These parasites are transmitted by the bites of infected female Anopheles mosquitoes. Here we use a deep learning technique called CNN to automatically extract the feautures from the cell image and automatically learn useful knowledge that is used to classify the cells as parasatized or uninfected.
The dataset is created by Lister Hill National Center for Biomedical Communications (LHNCBC), part of National Library of Medicine (NLM).They have carefully collected and annotated this dataset of healthy and infected blood smear images.

<img src="https://github.com/yoursenpai69/malaria-cell-recognition-177/blob/main/dataset.png" alt="not available" title="Optional title">

## Neural Network Model

<img src="https://github.com/yoursenpai69/malaria-cell-recognition-177/blob/main/nn_arch.JPG" alt="not available" title="Optional title">

## DESIGN STEPS

### STEP 1:
Download and load the dataset to colab. After that mount the drive in your colab workspace to access the dataset.

### STEP 2:
Use ImageDataGenerator to augment the data and flow the data directly from the dataset directory to the model.

### STEP 3:
Split the data into train and test.

### STEP 4:
Build the convolutional neural network

### STEP 5:
Train the model with training data

### STEP 6:
Evaluate the model with the testing data

### STEP 7:
Plot the performance plot

## PROGRAM

https://github.com/yoursenpai69/malaria-cell-recognition-177/blob/main/Ex04.ipynb

## OUTPUT

### Training Loss, Validation Loss Vs Iteration Plot

<img src="https://github.com/yoursenpai69/malaria-cell-recognition-177/blob/main/plt.JPG" alt="not available" title="Optional title">

### Classification Report

<img src="https://github.com/yoursenpai69/malaria-cell-recognition-177/blob/main/class_report.JPG" alt="not available" title="Optional title">

### Confusion Matrix

<img src="https://github.com/yoursenpai69/malaria-cell-recognition-177/blob/main/conf_matrix.JPG" alt="not available" title="Optional title">

### New Sample Data Prediction

<img src="https://github.com/yoursenpai69/malaria-cell-recognition-177/blob/main/output.JPG" alt="not available" title="Optional title">

## RESULT
Successfully developed a convolutional deep neural network for Malaria Infected Cell Recognition.
