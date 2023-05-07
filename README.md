# Ukraine-Russia Conflict on Twitter
This repository holds an attempt to apply lexicon-based sentiment analysis on tweets about the ongoing Ukraine-Russia conflict using data from ‘Ukraine Conflict Twitter Dataset’ on Kaggle. 

# Overview
The task is to determine the positive and negative sentiment expressed by users located in different states in the USA on Twitter about the ongoing Ukraine-Russia conflict.  
The approach in this repository formulates the problem as classification task, using AFINN lexicon to compute the sentiment scores of each state about the topic. The sentiment scores of the expression Republican and Democrat states on April 1st, 2022 computed. According to results Tennesse was the most positive state while Delaware was the most negative (exculing the territories.

# Summary of Workdone

  Data
   Type: CSV files (seperated for each day)
   Size: 15 GB 
  
  Preprocessing/Clean up
    - United States located English tweets separated.
    - URLs, mentions, hashtags, special characters and stop words removed.
    - All text converted to lowercase
    - Lemmatization performed.
    
  Data Visualization
  
  A bar graph comparing sentiment scores of states and a word cloud provided.
  
# Problem Formulation
    Input: Text
    Output: Sentiment Scores
    Lexicon Used: AFINN
    
# Conclusions
  
  The results showed majority of the states were negative through the conflict. Pennsylvania was almost neutral. Tennnese, Idaho, New York were leading the positive scores while people Delaware, Iowa, Oklahoma and Illinois were leading the negative population which is the majority.
  
# Future Work

  The sentiment analysis can be done on all the data which includes data from March 1st, 2022 to March 1st, 2023. 
  
# Overview of Files in Repository

April 1 2022.ipynb: Data preprocessing done on April 1st, 2022 data and sentiment scoring.
Data Preprocessing.ipynb: Data preprocessing attempt on the entire dataset.

# Citations
