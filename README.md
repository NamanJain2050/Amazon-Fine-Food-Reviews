# Amazon-Fine-Food-Reviews
This notebook showcases my analysis on Amazon-Fine-Food-Reviews dataset. (Source: https://www.kaggle.com/snap/amazon-fine-food-reviews)
The objective here is to <b> determine the polarity of reviews given in the dataset </b>. We have to correctly classify each review as positive or negative.
This is a <b> Supervised Learning </b> problem.

I have used following representations of our review text (I've used the each representation seperatley):
1. Unigram and Bigram BOWs
2. Unigram and Bigram TF-IDF
3. Avg-Word2Vec representation using Google New's pretrained dataset.
4. TF-IDF-weighted Word2Vec representation using Google New's pretrained dataset.
5. Avg-Word2Vec representation by training Word2Vec on Amazon reviews data.
6. TF-IDF-weighted Word2Vec representation by training Word2Vec on Amazon reviews data.
