# Detecting depression from Twitter texts - NLP Project

## Project Overview

 1. The algorithm predicts depression from Twitter texts with an accuracy of 75%
 2. The data was gathered from a provided dataset on Kaggle
 3.  Performed feature engineering on dataset's columns
 4. Explored the data through Wordclouds and histograms
 5. Generated new text based off of provided Twitter messages
 6. Created a pipeline for predicticting if a certain text message belongs to a person suffering from depression
 
 ## Code & Resources used
 
 1. Python version 3.7
 2. Packages: numpy, pandas, spacy, sklearn, keras
 3. Udemy link: [NLP](https://www.udemy.com/course/nlp-natural-language-processing-with-python/)
 4. Youtube links: [link1](https://www.youtube.com/watch?v=LHXXI4-IEns) [link2](https://www.youtube.com/watch?v=8HyCNIVRbSU&t=517s)
 
 ## Data - A better understanding
 
 Data was collected from "Sentiment140 dataset with 1.6 million tweets" dataset on Kaggle.
 The tweets are evenly chosen: 80.000 originating from people diagnosed with depression and the same amount of tweets are from "healthy" individuals.
 
 ## Feature Generation
 
 1. Transformed "Time" column into a datetime object so that we can call attributes off of the elements.
 2. We added another columns consisting of the lengths of the messages
 3. Dropped columns which were no longer useful
 4. Checked if there were any blank texts
 
 ## EDA
 
 A sneak peak from inside the project:
 
 ![alt text](https://github.com/CristianMihalceanu/NLP-Project/blob/main/length.PNG)
 
 ![alt text](https://github.com/CristianMihalceanu/NLP-Project/blob/main/wordcloud.PNG)
 
 ## Text Generation
 
 1. Provided a brief explanation of RNN and LSTM
 2. Created a neural network and used backpropagation to train it on our data in order to generate a new word based off of 50 previous ones
 
 ## Model Performance 
 
 Our model for predicting whether a person suffers from depression achieved 75% accuracy
 
 ## Productionization
 
 Following the result of the algorithm, an individual should be adviced to visit a professional psychologist or be provided a chatbot.
 
