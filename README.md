# Apples_Tomatoes_ImageClassification

Apple or Tomato? Binary Image Classification

In this project, we will make a binary classification model that can identify whether it is an apple or a tomato in the image.
Apples and tomatoes share some common characteristics such as the round shape or the red color.
It might be a tricky work to train a model properly, so that it can differntiate the two different obejcts. 

....

This is a basic exercise to develop a image classifier with Tensorflow. It can be used as a basic guidline to create a model from a pretrained one. 

The dataset can be downloaded from https://www.kaggle.com/datasets/samuelcortinhas/apples-or-tomatoes-image-classification/code?datasetId=2702329&sortBy=voteCount

To summarize the result, we were able to develop a model that has made a quite good prediction with the test dataset. The accuracy score was 92%. 
We first experimented with our fine-tuned pretrained model of InceptionResnet, different pretrained models can be used to make further experiments


> correction => input shape is 3 dimensional, meaning -> 299*299*3.  3 is because the image is a RGB color image
