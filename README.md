# MSc_AD_Detection_Project
This is my Masters Dissertation project code and dataset repository

The code is available in the code folder

Skullstripping_and_FeatureExtraction_slicing .ipynb and CNN_models.ipynb was run on Google Colab Pro

ImageData_Preparation_and_Preprocessing was run on the local machine

#Project Description

Alzheimer’s Disease is a progressive brain disorder that causes memory loss and changes in cognitive abilities of patients and is one of the major causes of dementia among older people. Due to the severity of this disease and the difficulty of diagnosing, many studies have been done by researchers using machine learning methods to detect Alzheimer’s Disease in patients. Even though many studies have been done in this field, most research has focused on the use of binary classification for AD detection also not much research has been done to find the best preprocessing techniques and model architectures needed to classify AD patients. Therefore, to address this problem, this project aims to build a 3-way multiclass classification model to find the best preprocessing, feature extraction technique and CNN architecture for AD detection. Several different preprocessing techniques such as resampling, image registration and skull stripping are experimented as well as slice based feature extraction on coronal and axial axis will be done to find the best preprocessing, feature extraction technique. Using this best preprocessing technique four state of the art 2D CNN models namely VGG16, InceptionResnet V2, EfficientNetB1, Inception V3 and two 3D CNN models namely a custom 3D CNN model and Resnet 3D CNN model will be trained to find the best CNN architecture for AD detection. When the results were analyzed, Skull stripped 5 middle Coronal slices without image registration was the best preprocessing and feature extraction technique and 2D VGG16 CNN model trained on the above mentioned preprocessed images was the best CNN architecture with an accuracy of 77.9% and AUC score of 0.870. This project was able to build a novel state of the art 3-way multiclass system with a higher accuracy than other studies and at the same time this project was able to analyze many preprocessing techniques and CNN architectures to find the best performing methods and models which is a significant contribution to the field of AD detection using machine learning.
