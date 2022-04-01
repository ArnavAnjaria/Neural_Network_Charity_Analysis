# Neural_Network_Charity_Analysis

## Overview

The purpose of this analysis was to use deep learning neural network techniques to analyze and classify the successfulness of charitable donations

## Results

- Data Preprocessing
  
  - The target for the model is IS_SUCCESSFUL
  
  - The features for the columns are
    
    - application type
    
    - affiliation
    
    - classification
    
    - use case
    
    - organization
    
    - income amt
    
    - special considerations
  
  - The columns that need to be removed are
    
    - ein
    
    - name

- Compiling, Training, and Evaluating the Model 
  
  - I selected 2 hidden layers with 80 and 30 nodes as it would allow for ample training with approximately 40 features. The activation function used was relu because it would give good speed for our binary sigmoid to be able to discern the output.
  
  - the model accuracy was below 75% at about 73% and so below the threshold of our target.
  
  - To increase the performance I tried to increase the nodes used, as well as change the activation layer model to a tanh to see if improved performance

## Summary

After attempting to make improvements to the model the best it was able to achieve was almost a 73% accuracy, which is still below our target of 75%. A classifier may be another approach that could be taken as the output of our data is binary. 