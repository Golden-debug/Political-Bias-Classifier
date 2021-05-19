
#Political Bias Classifier.


#### Data Source:
https://www.kaggle.com/snapcrack/all-the-news


#### Skills Demostrated
-TensorFlow and Keras
-Understanding Neural Network Fundamentals and structures
-Underestanding Natural Language processing fundamentals
-Using Text Encoding with Dummies
-Using Text encoding with Google's Universal Sentence Encoder
-Data augmentation


## Overview
This project uses a neural network to classify political bias in news articles. In order to classify the bias I developed labels of political bias based on the publisher of the news article. These labels were assigned based on political bias designations found online on allsides.com and adfontesmedia.com. This was done to avoid injecting my personal biases into the labels. Based on what is found in these resources I identified conservative articles with a 0 and liberal articles with a 1. I deliberaly excluded media sources known to be politically neural on average and selected the more biased publishers from the dataset. 

The end result of this process was a political bias classifier that could identify the bias labels I assigned with an accuracy of 93% on test set from publishers used in training. When used on the entire dataset the accuracy of the model fell to around 85%. Given that many of the articles in the dataset likely did not conform to the biases that I was assigning them I consider this to be a good result. 
