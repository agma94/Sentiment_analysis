This project was developed as a final assignment at Data Science bootcamp organised by Kodołamacz.

The subject of the project was sentiment analysis of reviews of beauty products from wizaz.pl - the largest Polish database with reviews 
on cosmetics.

The first step of analysis was data collection. The code used for web scraping can be found in 00_Web scraping.ipynb. Sentiment
analysis is presented in 01_Sentiment analysis.ipynb. The goal of the project was to develop a classification model, which would 
assess whether a review was positive, negative or neurtal. A few types of models have been tested (Naive Bayes, logistic regression,
random forests and SVM) and logistic regresstion was selected as the best performing one. At the end, the inspection of most relevant 
features affecting the sentiment of reviews was performed.
