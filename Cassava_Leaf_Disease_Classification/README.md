# CASSAVA

Cassava Leaf Disease Classification model

# Description 
This project database comes from Kaggle. The goal is to create a model which can identify the type of disease present on a Cassava leaf image.

2 different methods were used to classify the images. The first method utilizes 5 pretrained models to obtain feature maps from each. Then this info is fed into a model.

The second method utilizes image flow_from_directory to feed images into a 6 CNN layer model.

Because of the inequality of images per label, we sample the data for each method so the numbers not so skewed.

# Technologies 
-Python 3.6

-Tensorflow 2.7

# Run the project
This project was created in Google Colab. The directories are addressed as such for my own Colab environment. There are comments in the code which show which lines must be updated for the code to work.

Download the project [data here](https://www.kaggle.com/mahmoudreda55/satellite-image-classification)

### There are several sections which can be executed:
-**Import libraries:** Required to execute code

-**Initilize variables:**  Required to execute code. The home_dir variable must be updated to the folder which houses the train_images folder.

-**View data:** Required to execute code. The path variable must be updated to a valid image location.

-**Data processing for transfer model and flow_from_dataframe:** Process data when using either of these models.

-**Data processing for flow_from_directory:** Process data when using this model.

-**Define and execute transfer learning model:** We find and save the best model for validation accuracy. You have the option to choose an individual pretrained model or several.

-**Define and execute flow_from_dataframe 6 CNN layer model:** We find and save the best model for validation accuracy.

-**Define and execute flow_from_directory 6 CNN layer model:** We find and save the best model for validation accuracy.

