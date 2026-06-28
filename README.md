# Introduction to Deep Learning Final Project

This project includes three different deep learning models implemented with Python and TensorFlow/Keras.

The main purpose of the project is to apply deep learning models on both image and text data, and compare their results.

## Models Used

- CNN for image classification
- LSTM for Turkish sentiment analysis
- Autoencoder for image reconstruction

## Datasets

Two datasets were used in this project:

- Intel Image Classification Dataset
- Turkish Movie Sentiment Analysis Dataset

The Intel Image Classification dataset was used for image classification and image reconstruction.  
The Turkish Movie Sentiment Analysis dataset was used for sentiment classification.

## Project Description

In the CNN part, natural scene images were classified into six classes: buildings, forest, glacier, mountain, sea, and street.

In the LSTM part, Turkish movie reviews were classified as negative, neutral, or positive.

In the Autoencoder part, the model learned a compressed representation of images and tried to reconstruct the original images.

## Technologies

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- scikit-learn
- Kaggle Notebook

## Results

| Model | Task | Result |
|---|---|---|
| CNN | Image classification | 0.8067 accuracy |
| LSTM | Turkish sentiment analysis | 0.3734 accuracy |
| Autoencoder | Image reconstruction | 0.0043 loss |


CNN gave the best classification result in this project.  
The LSTM model had difficulty separating Turkish sentiment classes, especially negative and neutral reviews.  
The Autoencoder model reconstructed the general structure of images, but small details were blurry.
