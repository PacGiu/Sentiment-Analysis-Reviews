# Sentiment-Analysis-Reviews

Sentiment Analysis: Here I go through some data exploration, and manipulation to build up a database that contains some paramenters for Sentiment Analysis. Using a quick NaiveBayesClassifier I build a score for each word that can be used to rank results (indipendently form their review scores)

This is a WIP, so comments and suggestions are more than welcome!

Many bits of this Kernel come from info and tutorials sparse around the internet, I will try to add the links to the major resources once I am done with the analysis, please bear with me!

Add columns, Clean columns and feel the data: I play a bit with the data to get confortable with it and get some new columns and lists that could be useful for better understanding of the dataset.

Create some useful function to play with words: I define some handy functions, some choices have been made for making them a bit faster (like using Toktok) as we will have to run this over the whole database (515K! my laptop is old...)

Finally, lets have some fun reading the top 3 best and worst reviews! 


This Kernel can be found at : https://www.kaggle.com/pacogiu/sentiment-analysis-from-hotel-reviews
