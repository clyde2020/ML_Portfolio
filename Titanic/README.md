# TITANIC

Predict survival on the Titanic

# Description 
This project database comes from Kaggle. The goal is to create a model which can predict who in the test data survived the Titanic shipwreck.

We fill in missing values in the data. Next we split the data to create a validation set. We process the data. Finally we transform the data into the format desired.

Several classifiers are used so the voting classifier can make a democratic decision.

Submission CSV file is created at the end for submission to Kaggle.

# Technologies 
Python 3.6

Tensorflow 2.7

# Run the project
This project was created in Google Colab. The directories are addressed as such for my own Colab environment. There are comments in the code which show which lines must be updated for the code to work.

Download the project [data here](https://www.kaggle.com/c/titanic/data)

## There are several sections which can be executed:
**Import libraries:** Required to execute code

**Initilize variables:**  Required to execute code. The host_folder variable must be updated to the folder which houses the downloaded data.

**Process data:** Required to execute code. This cleans and processes the data before transformation.

**Models:** We using a voting classifier to make predictions on the test data. Submission CSV file is created to submit to Kaggle for actual score.

