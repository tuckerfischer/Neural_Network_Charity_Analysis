# Neural_Network_Charity_Analysis

## Overview

In this project we were tasked with building a neural network in order to determine if an applicant for a charity fund will be successful if funded.

## Results

### Data Preprocessing

Before doing the analysis we removed the companies name and identifier. The features we took in to consideration were:

  1. Application Type
  2. Affiliated secor or industry
  3. government organization classification
  4. Use case for funding
  5. Organization type
  6. Active status
  7. Income classification
  8. Special considerations for application
  9. Funding amount requested

The target of this analysis was whether not not the money was used effectively.

### Compiling, Training, and Evaluating the Model

In our model we had 4 hidden layers with five nodes each. We had three relu activation, and two tanh activation function in the hidden layers. I was not able to achieve the target accuracy of 75% coming in at 53% max efficiency. To increase the models performance I would want to add more hidden layers and see what combination of activation functions would optimize performance. 

## Summary

I was able to achieve 53% accuracy in predicting whether or not money chosen going to a company would be used effectively. While this is not enough accuracy to replace the decision making process it is capable in aiding it. To improve this in the future I would try add in more variables or sequentially remove those already in the model in order to see if there are confounding factors or factors that hold more weight. 
