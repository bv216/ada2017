# Title
Analysis of the influence of popularity on Amazon reviews.

# Abstract

This project will analyze the influence of popularity on Amazon reviews from different points of views, such as popularity of the reviewer, of the product, of the amount of reviews for the product and of the helpfulness reviews. To develop it we are going to use two datasets, the main one is going to be the **Amazon Reviews Dataset** and its ¬-_metadata_ while the second, that is going to complement the first, is the **Million Song Dataset**.
For many buyers, it’s clear that reviews are helpful and take part in their purchase decisions but we wonder who do them, is it just because of the motivation of knowing that you are helping someone? 
These commentary from customers are part of the success of Amazon and our study will let us explore what motivates reviews and which type of buyers get more information from them. 


# Research questions
* Q1: How has the amount of reviews changed during time? Is this constant on every category? 
* Q2: Relation between price of the product and the amount of reviews.
* Q3: Relation between category of the product and the amount of reviews.
* Q4: Evolution of the number of reviews along time. Is the amount of comments affecting to the possible new comments? Is the helpfulness of the comments affecting?
* Q5: Are the top reviewers doing more helpful reviews? Is there any relation between top reviewers and the categories?
* Q6: Is there relation between the popularity of the product and its commentaries?
* Q7: Does the reviews affect the evolution of the product price?


# Dataset
The main dataset we are going to use is **Amazon Reviews**, where we can find the reviews done in Amazon.com from May 1996 to July 2014. Our idea is to use the _reviewerID_ to know about the top reviewers, _asin_ for recognizing products, the _reviewTime_ to know when these reviews are done, the _overall_ score to match it with the top reviewers, products and also with the _helpful_ field to see if there's any relation between scores and helpfulness. 
We plan to enrich this dataset with the **Million Song Dataset**, to check if the Digital Music Category products reviews are related with their popularity from the music dataset by matching the _title_ from the Song Dataset with the _title_ from _metadata_ placed in the Amazon Dataset.


# A list of internal milestones up until project milestone 2
We are planning meeting every week for 3 hours to comment our individual progress and check the project. While working on it individually contacting by Mattermost.
Our calendar is going to be the following:
  > **Week 1**: Exploratory analysis of data. Starting notebook with dataframes and fixing data. 

  > **Week 2**: Plotting data to answer our questions.

  > **Week 3**: Analyze information from plots and do some more research on assumptions if needed.
  
  > **Week 4**: Wrapping analysis, check every comment and prepare documentation to submit this second milestone.

# Questions for TAa
No questions at this moment.