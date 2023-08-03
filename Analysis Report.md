# Report

## Overview of the Analysis

This analysis model is being used to help the fictional nonprofit foundation Alphabet Soup. The foundation wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With our knowledge of machine learning and neural networks, we used the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

## Results

### Data Processing

* The target variable is "IS_SUCCESFUL" column from "application_df"
* The feature variable is definied by dropping the column "IS_SUCCESSFUL" from the original dataframe. Every other column from "application_df" are the feature variables. 
* Columns that were dropped or removed are - "EIN" and "NAME". They are neither targets nor features, thus the removal from the dataset. 

## Compiling, Training, and Evaluating the Model

* I used 8 hidden_nodes_layer1 and 5 hidden_nodes_layer2 for the first attempt. These were chosen randomly and the rest of the tries were based upon them. 
* I was not able to achieve 75% model accuracy target. 
* To increase the model performance, I added more layers, removed columns, increased the number of hidden nodes and also switched the activation functions associated with each layer. 

## Summary

The model that I developed was about 72% accurate in predicting the classification problem. The accuracy can be increased by doing more data clean up or using a model with varying activation functions. Increasing the number of attempts may also increase accuracy. 