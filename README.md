# IMDb-Movie-Review-Sentiment-analysis
This is a mini project, in which i designed the ROBERTA model with pytorch for sentiment analysis and the dataset I used is IMDb-Movie-Review. The data contain raw text and its sentiment. 
## ROBERTA 
A robustly optimized method for pretraining natural language processing (NLP) systems that improves on Bidirectional Encoder Representations from Transformers, or BERT, the self-supervised method released by Google in 2018. BERT is a revolutionary technique that achieved state-of-the-art results on a range of NLP tasks while relying on unannotated text drawn from the web, as opposed to a language corpus that’s been labeled specifically for a given task.

## Dataset
(https://www.cs.cornell.edu/people/pabo/movie-review-data/)

## Libraries Needed
- Transformers
- contractions
- torch
- sklearn
- numpy
- pandas
- nltk
- re
- glob
- os
- inspect
- Pytorch

## Project layout
- Load the Training data
- Data pre-processing and Data cleanning
- Exploratory data analysis
- Dataloader
- Model Creation
- Model Training
- Save Model
- Model validation

## Description
In this work i have done pre-processing including, stemming, stop words and punctuation removal. After that i have performed some data analysis to analysis the data, then I designed the Robert a model class and custom data-class to transformed the data into inputs-ids attention-mask and tokens types-ids. After converting data into required format, I trained the model by using pretrained model (ROBERTa). Then perform the testing and plot Confusion matrix and other evaluation criteria are shown as well.
Also I have mentioned all the comments and heading in the code for your understanding



