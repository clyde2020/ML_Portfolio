# Title
SATELLITE

Satellite Remote Sensing image interpretation model 

# Description 
This project database comes from Kaggle, Satellite image Classification Dataset-RSI-CB256. The goal is to create a model which can interpret 4 different classes of remote sensing (RS) images.

2 different methods were used to classify the images. The first method utilizes 5 pretrained models to obtain feature maps from each. Then this info is fed into a model for an accuracy of XXX.

The second method utilizes image flow_from_directory to feed images into a 6 CNN layer model for an accuracy of XXX.

Because of the inequality of images per label, we sample the data for each method so the numbers are equal.

# Technologies 
Python 3.7 

Tensorflow X.XX

# Run the project
This project was created in Google Colab. The directories are addressed as such for my own Colab environment. Setting up your source, train, and valid folders in the 2nd code block should allow the project to run.

Data can be downloaded from:  https://www.kaggle.com/mahmoudreda55/satellite-image-classification

