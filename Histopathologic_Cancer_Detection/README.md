# HCD

Histopathologic Cancer Detection model

# Description 
This project database comes from Kaggle. The goal is to create a model which can identify metastatic tissue in histopathologic scans of lymph node sections.

Flow_from_directory is utilized to feed images into a 6 CNN layer model. Afterwards, the test data is fed into the model, and the predictions CSV file is generated for submission into Kaggle.

Because of the inequality of images per label, we sample the data so the model can train on equal representation of images.

# Technologies 
-Python 3.6

-Tensorflow 2.7

# Run the project
This project was created in Google Colab. The directories are addressed as such for my own Colab environment. There are comments in the code which show which lines must be updated for the code to work.

Download the project [data here](https://www.kaggle.com/c/histopathologic-cancer-detection/data)

### There are several sections which can be executed:
-**Import libraries:** Required to execute code

-**Initilize variables:**  Required to execute code. The initial_dir variable must be updated to the folder which houses all of the downloaded folders.

-**View data:** Not required, only for visualizing data.

-**Process data:** Process data to feed into model.

-**Define and execute model:** We find and save the best model for validation accuracy.

-**Get predictions and create submission CSV file:** We get predictions from the test data, then we process the CSV file for submission into Kaggle.

-**Get AUC:** We find the area under the curve metric.


