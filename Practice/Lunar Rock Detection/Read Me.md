This is challenge posted in Hacker earth for detection of lunar rocks with the training set images which counts to 5000. 

Let me explain it one by one:

Importing the required libraries:
Importing all required libraries from os to keras.

Saving the directories after unpacking:
Saving the directory as new variable which is used to fetch the data (Images in this case).

Converting the raw images to raw matrix as img with opencv:
Converting the images to matrices inorder to peform some filterations. Lets assume if the full image is given and the key to crack is
given in particular pixels, then it is wise to covert into matrix in which we can play with.

Encoding the lables to it:
Creating another set of variable inorder to encode the lables which specifies the rock category.

Test Train split:
Spliting the given data into test and train dataset for better learning rate and evaluation.

CNN model:
Creating a sequential classifier with a basic structure of 1 input layer, 1 ouput layer and 3 hidden layers

Data populating:
Increasing the data using data generator which inturn increases the data for training and improves the learning rate.

Compiling and fitting:
Basic compilig and fiting the model.

Saving the model as Dump:
Saving the model as .joblib file for future use.
