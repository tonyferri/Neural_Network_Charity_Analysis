# Neural_Network_Charity_Analysis
Module 19 Challenge

## Overview of the Analysis:
Create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results: Using bulleted lists and images to support your answers, address the following questions.
* Data Preprocessing
  * What variable(s) are considered the target(s) for your model?
    * The column "IS_SUCCESSFUL" was used as the target
  * What variable(s) are considered to be the features for your model?
    * All other columns except for "EIN" and "NAME"
  * What variable(s) are neither targets nor features, and should be removed from the input data?
    * Columns "EIN" and "NAME" were considered irrelevant and removed from the data set

* Compiling, Training, and Evaluating the Model
  * How many neurons, layers, and activation functions did you select for your neural network model, and why?
    * 24 and 12 neurons
    * 2 hidden layers
    * Relu for hidden layers; Sigmoid for output layer
    * The template from the canvas activity was used because the amount of data was similar and seemed to be a good starting point
  * Were you able to achieve the target model performance?
    * No, my initial accuracy before trying any optimization was 73%
  * What steps did you take to try and increase model performance?
    * Changed bin sizes
    * Add neurons
    * Add hidden layers
    * Change activation functions
    * Changed number of epochs

## Summary:
* Summarize the overall results of the deep learning model
  * The different optimizations did not have a major impact on the accuracy

## Additional info
  * Since I wanted to investigate more than three different optimization, I decided to create a different file for each optimization.  Also, it was more beneficial to show each output seperately.
  * I also included a random forest classifier as a comparison

## Pics:

![Module 19 Summary](https://github.com/tonyferri/Neural_Network_Charity_Analysis/blob/main/resources/Module%2019%20Summary.png)