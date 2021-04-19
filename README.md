#IMDb-Movie-Review-Sentiment-analysis
This is a mini project, in which i provide the model for sentiment analysis and the dataset I used is IMDb-Movie-Review. The data contain raw text and its sentiment. 
## Dataset
(https://www.cs.cornell.edu/people/pabo/movie-review-data/)

##Libraries Needed
- transformers
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

##Description
In this work i have done pre-processing including, stemming, stop words and punctuation removal. After that i have performed some data analysis to analysis the data, then I designed the Robert a model class and custom data-class to transformed the data into inputs-ids attention-mask and tokens types-ids. After converting data into required format, I trained the model by using pretrained model (ROBERTa). Then perform the testing and plot Confusion matrix and other evaluation criteria are shown as well.
Also I have mentioned all the comments and heading in the code for your understanding



