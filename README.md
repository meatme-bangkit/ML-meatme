# Machine Learning Path Repository Meatme
This repository used for image processing and creating model detection for MeatMe. We use dataset from kaggle then we built model using CNN method. At the end of the model, we will transform the model to tflite.

## Workflow
Search Image Dataset :arrow_right: Image Preprocessing :arrow_right: Creating Model Detection :arrow_right: Convert to TFLite :arrow_right: Deploy to Android

## Image Dataset
We gather our image Dataset from Kaggle and we separate the images into 4 classes : 
1. 'Fresh'
2. 'Half Fresh'
3. 'Spoiled'
4. 'Not Valid Image'

## Image Preprocessing 
In Image Preprocessing, our team performs two image preprocessing techniques:
1. Normalization 
2. Data Augmentation

## Creating Model Detection
We create model with method CNN and we train with 100 epoch. After that, we plot the model result for accuracy and loss.

![Screenshoot from .ipynb for Training and Validation Accuracy](https://github.com/meatme-bangkit/ML-meatme/assets/125948229/520b662a-aebd-49c3-9137-7b0a6fd849ca)

![Screenshoot from .ipynb for Training and Validation Loss](https://github.com/meatme-bangkit/ML-meatme/assets/125948229/0ebb9a39-0974-4198-afab-467922d4b0f2)
