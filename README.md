# Noisy-Fracture-Images-Enhancement-Using-PCA
ABSTRACT:
PCA is a useful statistical technique that has found application in fields such as Image Denoising, Image compression, Image Feature Extraction and Facial recognition. It is a way of identifying patterns in data, and expressing the data in such a way as to highlight their similarities and differences. Since patterns in data can be hard to find in data of high dimension, where the luxury of graphical representation is not available, PCA is a powerful tool for analysing data. The other main advantage of PCA is that once you have found these patterns in the data, and you compress the data, ie. by reducing the number of dimensions, without much loss of information. 
Here we demonstate how to use it for Image Denoising and Image Compression as well.

OBJECTIVE:
The primary objective of this project is to demonstrate how PCA can be used for Image Denoising and Image compression without affecting the important features of the image by doing a comparison of performance of different classifiers on both original as well as noisy images.

DATASET USED:
https://www.kaggle.com/datasets/vuppalaadithyasairam/bone-fracture-detection-using-xrays/

METHODOLOGY USED:
Original Image->PCA:Apply classifiers
Noisy Image->PCA:Apply classifiers
Binary classifiers used:
1.	K-Nearest Neighbours
2.	Support Vector Machine
3.	Logistic Regression
4.	Decision Tree classifier
5.	Random Forest Classifier

CHANGES TO BE MADE TO THE CODE TO RUN IN LOCAL:
1. Make 2 folders, in one store fractured images and in another store not fractured images.
2. Correct the paths to these folders in jupyter notebook.
Hurrah! Now your code is ready to be run. Hope it works fine. 
