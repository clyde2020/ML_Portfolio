# HCD

Histopathologic Cancer Detection model

# Description 
This project database comes from Kaggle. The goal is to create a model which can identify metastatic tissue in histopathologic scans of lymph node sections.

Flow_from_directory is utilized to feed images into a 6 CNN layer model. Afterwards, the test data is fed into the model, and the predictions csv file is generated for submission into Kaggle.

Because of the inequality of images per label, we sample the data so the model can train on equal representation of images.

# Technologies 
-Python 3.6

-Tensorflow 2.7

# Run the project
This project was created in Google Colab. The directories are addressed as such for my own Colab environment. There are comments in the code which show which lines must be updated for the code to work.

Download the project [data here](https://www.kaggle.com/c/histopathologic-cancer-detection/data)

### There are several sections which can be executed:
-**Import libraries:** Required to execute code

-**Initilize variables:**  Required to execute code. The home_dir variable must be updated to the folder which houses the train_images folder.

-**View data:** Required to execute code. The path variable must be updated to a valid image location.

-**Data processing for transfer model and flow_from_dataframe:** Process data when using either of these models.

-**Data processing for flow_from_directory:** Process data when using this model.

-**Define and execute transfer learning model:** We find and save the best model for validation accuracy. You have the option to choose an individual pretrained model or several.

-**Define and execute flow_from_dataframe 6 CNN layer model:** We find and save the best model for validation accuracy.

-**Define and execute flow_from_directory 6 CNN layer model:** We find and save the best model for validation accuracy.


