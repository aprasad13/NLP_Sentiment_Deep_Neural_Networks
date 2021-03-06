# NLP_Sentiment_Deep_Neural_Networks

This notebook shows the implementation of <strong>Sentiment Analysis</strong> using Google's Trax. 

Using this user can get the sentiment of a sentence (positive/negative)

Click on [Jupyter Notebook](https://github.com/aprasad13/NLP_Sentiment_Deep_Neural_Networks/blob/master/Sentiment_Deep_Neural_Networks.ipynb) to access the detailed code.

## Overview:
- Build/design a model using layers
- Train a model using a training loop
- Use a binary cross-entropy loss function
- Compute the accuracy of the model
- Predict using a custom imput

## Following steps are being followed to complete the project:
- Imported the necessary libraries
- Data: I have used twitter tweets to evaluate the model
- Build the vocabulary based on the training data and then converted the tweets to tensors
- Created a batch generator for the tweets
- Defined the network structure using classifier function
- Used <strong>Cross-Entropy</strong> as loss function and <strong>Adam</strong> as optimizer 
- Evaluated the model with an <strong>accuracy of 99.31%</strong>
- Tested with a custum input to check if the model predict the sentiment of a complicated sentance or not
