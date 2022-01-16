# CASSAVA

Cassava Leaf Disease Classification model

# Description 
This project database comes from Kaggle. The goal is to create a model which can identify the type of disease present on a Cassava leaf image.

2 different methods were used to classify the images. The first method utilizes 5 pretrained models to obtain feature maps from each. Then this info is fed into a model for an accuracy of 97%.

The second method utilizes image flow_from_directory to feed images into a 6 CNN layer model for an accuracy of 92.7%.

Because of the inequality of images per label, we sample the data for each method so the numbers not so skewed.

# Technologies 
-Python 3.6

-Tensorflow 2.7

# Run the project
This project was created in Google Colab. The directories are addressed as such for my own Colab environment. Setting up your source, train, and valid folders in the Initialize variables code section should allow the project to run.

Download the project [data here](https://www.kaggle.com/mahmoudreda55/satellite-image-classification)

### There are several sections which can be executed:
-**Import libraries:** Required to execute code

-**Initilize variables:**  Required to execute code.

-**View image:** Required to execute code. The path variable must be updated to a valid image location.

-**Set up flow_from_dataframe:** Create flow_from_dataframe for data into models.

-**Set up flow_from_directory:** Create flow_from_directory for data into models.

-**Get feature maps from pretrained models:**  This creates a function which extracts the feature maps from 5 pretrained models.

-**Define and execute transfer learning model:** We find a best model of 97% accuracy versus the validation data.

-**Process data for 6 CNN layer model:** Create flow_from_directory for data into models.

-**Define and execute 6 CNN layer model:** We find a best model of 92.7% accuracy versus the validation data.

-**Evaluate the validation predictions a bit further:**  Reload the best model, flow validation images 1 at a time through the model for predictions, evaluate the accuracy
