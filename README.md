# Machine Learning Path Repository Meatme
This repository used for image processing and creating model detection for MeatMe. We use dataset from kaggle then we built model using CNN method. At the end of the model, we will transform the model to file .H5

## Workflow
Search Image Dataset :arrow_right: Image Preprocessing :arrow_right: Creating Model Detection :arrow_right: Convert to file .H5 :arrow_right: Deploy to Android with API

## Image Dataset 
we took the meat dataset from the kaggle public dataset for meat freshness:
1. 'Fresh'
2. 'Half Fresh'
3. 'Spoiled'

Then, we added the not meat class to the dataset, so that the model can also detect whether the input image is a meat image or not. These are the classes:
1. 'Fresh'
2. 'Half Fresh'
3. 'Spoiled'
4. 'Not Meat'

## Image Preprocessing 
In Image Preprocessing, our team performs two image preprocessing techniques:
1. Normalization and Resize Image Dataset 
2. Data Augmentation

## Creating Model Detection
We create model using a Convolutional Neural Network (CNN) implemented using the Sequential model in Keras.
After conducting various experiments on the model to get good accuracy, we trained the model and the accuracy of the model reached 96 percent. Here is the model summary:

![image](https://github.com/meatme-bangkit/ML-meatme/assets/134268378/ed3d3b59-d496-4a7b-9070-9c4a93570b67)

After that, we plot the model result for accuracy and loss.

![Screenshoot from .ipynb for Training and Validation Accuracy](https://github.com/meatme-bangkit/ML-meatme/assets/125948229/520b662a-aebd-49c3-9137-7b0a6fd849ca)

![Screenshoot from .ipynb for Training and Validation Loss](https://github.com/meatme-bangkit/ML-meatme/assets/125948229/0ebb9a39-0974-4198-afab-467922d4b0f2)
