# Brain_Tumor_Detection_CNN_Models

This project aims to classify whther a subject has brain tumor or not, via MRI image slices by building a CNN model (VGG-16).

## A. Datasets
1. Kaggle dataset
   Size : 8 MB

This dataset contains MRI scans of 2 classes, YES - 1 encoded for tumor, NO - 0 encoded for no tumor.
URL : https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection


2. Brain Tumor Dataset
   Made publicly available by Cheng, Southern Medical University
   Size : 838 MB

This dataset contains 3064 Brain MRI images in .mat format, which was converted to .npy format for better visualization.
URL : https://figshare.com/articles/dataset/brain_tumor_dataset/1512427/5?file=7953679


## B. What is VGG-16 ? 

VGG-16 is a convolutional neural network that 16 layers deep. The model loads a set of weights pre-trained on ImageNet. The model achieves 92.7% top-5 test accuracy in ImageNet, which is a dataset of over 14 million images belonging to 1000 classes.


Ref : https://medium.com/@nutanbhogendrasharma/deep-convolutional-networks-vgg16-for-image-recognition-in-keras-a4beb59f80a7

