# Miscillanious Scripts

A collection of scripts for mining and analyzing data from Reddit. 

## Reddit Scraper `reddit_scraper.ipynb`

This notebook scrapes posts and comments from a specified subreddit using PRAW (Python Reddit API Wrapper).

## Multiprocessing Reddit Scraper `pmaw_scraper.ipynb`

This notebook uses a much simpler API for scraping large amounts of Reddit data. 

## NLP Experiments `nlp_experiments.ipynb`

Analyzing and exploring large amounts of Reddit text. Named entity recognition, n-gram frequency analysis, word vectorization, dimensionality reduction, topic modeling, and more. 

## Subreddit Database Creation `subreddit_database_creation.ipynb`

The notebook demonstrates how to extract massive amounts of Reddit data to build a map of subreddits.

## Subreddit Visualization `subreddit_visualization.ipynb`

Using the database, we create "subreddit vectors" and then convert these vectors into a 2D map. All of the subreddits are then plotted in an interactive visualization. 

# College Computer Science Project

End-to-end machine learning project, with the purpose of analyzing political presences on Reddit. In particular, comment data is scraped from two diametrically opposed political communities (liberal vs. conservative). Exploratory data analysis is performed to discover new insights, and a binary classification model is trained to see if a single comment from either community can be predictive of political association.

## Reddit Comment Preprocessing `comment_preprocessing.ipynb`

This notebook explains and demonstrates all of the steps for sampling, cleaning, and exploring the data. 

## Political Association Predictive Models `predictive_models`

This notebook shows how to use the preprocessed comment data to train models that predict political association. 
