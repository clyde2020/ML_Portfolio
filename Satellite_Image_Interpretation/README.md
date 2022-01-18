# SATELLITE

Satellite Remote Sensing image interpretation model 

# Description 
This project database comes from Kaggle, Satellite image Classification Dataset-RSI-CB256. The goal is to create a model which can interpret 4 different classes of remote sensing (RS) images.

2 different methods were used to classify the images. The first method utilizes 5 pretrained models to obtain feature maps from each. Then this info is fed into a model for an accuracy of 97%.

The second method utilizes image flow_from_directory to feed images into a 6 CNN layer model for an accuracy of 92.7%.

Because of the inequality of images per label, we sample the data for each method so the numbers are equal.

# Technologies 
Python 3.6

Tensorflow 2.7

# Run the project
This project was created in Google Colab. The directories are addressed as such for my own Colab environment. Setting up your source, train, and valid folders in the Initialize variables code section should allow the project to run.

Download the project [data here](https://www.kaggle.com/mahmoudreda55/satellite-image-classification)

### There are several sections which can be executed:
**Import libraries:** Required to execute code

**Initilize variables:**  Required to execute code. The host_folder variable must be updated to the folder which houses the downloaded data folder.

**View data:** Required to execute code.. The path variable must be updated to a valid image location.

**Process data for image dataframe:** This designates and creates folders for the images which are then split. Complete dataframe is created.

**TRANSFER LEARNING**
**Process data for transfer learning:** This creates numpy arrays for the images and labels, rescales the data, and readies it for the transfer models.

**Get feature maps from pretrained models:**  This creates a function which extracts the feature maps from 5 pretrained models.

**Define and execute transfer learning model:** We find a best model of 97% accuracy versus the validation data.

**6 CNN LAYER MODEL**
**Process data for model:** Create flow_from_directory for data into models.

**Define and execute model:** We find a best model of 92.7% accuracy versus the validation data.


**Evaluate the validation predictions a bit further:**  Reload the best model, flow validation images 1 at a time through the model for predictions, evaluate the accuracy
