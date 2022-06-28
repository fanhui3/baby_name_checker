# Baby_name_checker
an NLP model to predict the gender of name. Great for parents to choose a gender neutral or distinctive Male/Female name for their newborn.


This project contains 2 modules.
* Training Module
* Predictor Module

You must have the following packages to run this project.
* numpy
* pandas
* re
* sklearn
* joblib
* tensorflow (pip install needed if running from anaconda)

## Training Module (no user input required)
No inputs needed from users. This module preprocess the training data, train the NLP model, and export the objects for the predictor module.
Viewer can observe the steps taken to train the model.
This module allows for project team to train better iterations without disrupting the functionality of the predictor module.

## Predictor module (user input required) 
This module shall predict the gender of the name user input.
Under the section "input name for prediction". Do the following: 
* names shall be in the form of list in between square brackets
* you can have insert multiple name through a comma separation
* e.g name = ["valerie"] or name = ["timmy", "tommy", "jerry"]

Thereafter, run the rest of the code and the result for the respective name shall be returned at the bottom of the page.
 
