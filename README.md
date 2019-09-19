# Amazon-Fine-Food-Reviews
This notebook showcases my analysis on Amazon-Fine-Food-Reviews dataset. (Source: https://www.kaggle.com/snap/amazon-fine-food-reviews). This is one the most elaborated analysis on AFR dataset you'll find out there.
The objective here is to train a model which can <b> determine the polarity of a review given to it. </b>. We'll split our original dataset into train and test data at the very begining. We'll use train dataset to train our model and test data to check the model's performance (obviously). This is a <b> Supervised Learning </b> problem.

## Data Cleaning
Steps followed to clean our data:
1. 

I have used following representations of our review text (I've used the each representation seperatley):
1. Unigram and Bigram BOWs
2. Unigram and Bigram TF-IDF
3. Avg-Word2Vec representation using Google New's pretrained dataset.
4. TF-IDF-weighted Word2Vec representation using Google New's pretrained dataset.
5. Avg-Word2Vec representation by training Word2Vec on Amazon reviews data.
6. TF-IDF-weighted Word2Vec representation by training Word2Vec on Amazon reviews data.
