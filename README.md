# Detection-of-Alzheimer-s-Disease-using-Deep-Learning
 
This repository has code that detects Alzheimer’s disease using Convolutional Neural Network in Tensorflow & Keras using MRI scans.
Dataset used is derived from ADNI (.nii extention) and preprocessed using SPM 12 software. 
# About the data:
The dataset consisted of 3 folders: AD, MCI, CN having 2995 Brain MRI scans. The folder AD had images of 982 scans suffering from AD, CN folder had 967 scans of normal people, MCI had 985 scans of people in intermediate stage between AD and CN.
# Data Preprocessing:  
Some basic preprocessing steps of Realignment, Slice Timing Correction and Normalization has been carried out using SPM12 software. After that clustering was carried out given in –
•	Clustering MRI.ipynb that consists of the code for k-means clustering that has been used for clustering the preprocessed MRI scans.
•	After this cropping of the brain was done to remove the redundant areas and the images were converted to .jpg format for easy usage.
# CNN Architectures:
The data has been splitted into 70% for training, 15% for validation and 15% for testing. After this famous CNN models have been applied for detection purpose - 
	GoogleNet96.ipynb is the file which consists of the final implementation of the project where GoogleNet is used and final output is shown with accuracy 96.81%.
	Resnet50.ipynb consists of the final implementation of the project where ResNet50  is used and final output is shown with accuracy 96.13%.
	Squeezenet_93.ipynb consists of the final implementation of the project where ResNet50  is used and final output is shown with accuracy 93.18%.
Computer specifications that was used are : 
Processor : Intel®Xeon®Silver 4108 CPU @ 1.80GHz
Installed RAM :8.00GB and 64 bit Operating System.
Software used for this is - Anaconda Individual Edition 2020.11 and all the code has been written on Jupyter notebook in Python.

I will happy to see contributions!
Thankyou.

