# Deep Learning for Heart Valve Disease Detection
This project consists of a set of codes used to automatically segment PCG signals and classify the segmented signals into normal or abnormal categories.
- The segmentation stage was implemented on Matlab R2021a
- The classification task was executed using Python 3.8.10 and some of the most common Machine Learning libraries, such as Pytorch 1.7.1 and Scikit Learn 1.0.2.
## How it Works?
1. You must have a database with PCG signals, they can be of different duration and sampling frequency.
2. The Matlab code will segment the PCG signals through the **main.mlx** file.
3. Segmented PCG signals are converted to scalogram images.
4. Scalogram images are classified by using two Convolutional Neural Networks (ResNet152 and VGG16) and the Transfer Learning technique.
