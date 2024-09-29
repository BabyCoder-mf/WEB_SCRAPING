Data Analysis Projects: Kenya Airways Reviews & Premier League Predictions

Overview

This repository contains two distinct projects:

Kenya Airways Customer Reviews Analysis – Focused on scraping and analyzing customer feedback on Kenya Airways services.

Premier League Top 4 Prediction – Involves scraping Premier League data and building a machine learning model to predict the top four teams in the league.

Kenya Airways Customer Reviews Analysis

Objective:

The goal of this project is to analyze customer reviews of Kenya Airways to identify key themes, perform sentiment analysis, and extract insights that can help improve customer satisfaction.

Key Steps:

Data Collection:

Scraped 459 reviews from SkyTrax using BeautifulSoup and Requests.

Data Preprocessing:

Cleaned text data by removing special characters, unnecessary whitespace, and stop words.
Tokenized and vectorized reviews for topic modeling and sentiment analysis.

Topic Modeling:

Implemented Latent Dirichlet Allocation (LDA) to extract 5 main topics:
Flight experience (seating, food, crew).
Service quality at Nairobi airport.
Boarding and flight operations.
Ticketing, payments, and luggage handling.
Flight delays and disruptions.

Sentiment Analysis:

Analyzed sentiments using text data, with the following distribution:
Positive reviews: 65.58%
Negative reviews: 33.99%
Neutral reviews: 0.44%

Visualization:

Created bar charts to visualize the top words in each topic.
Created pie charts to display the distribution of sentiments.

Tools:
Web Scraping: BeautifulSoup, Requests
Text Processing & Topic Modeling: Pandas, CountVectorizer, LDA
Visualization: Matplotlib
Premier League Top 4 Prediction

Objective:

This project aims to predict which teams will finish in the top four positions of the Premier League, based on match data and team performance metrics.

Key Steps:

Data Collection:

Web scraped Premier League data (team statistics, player performances) using Selenium and BeautifulSoup.

Data Preprocessing:


Cleaned and formatted the data using Pandas for analysis.
Handled missing values, outliers, and normalized relevant features.
Exploratory Data Analysis (EDA):

Conducted EDA to uncover key patterns and trends in team performance.
Visualized team standings, match outcomes, and player statistics using bar and line charts.

Modeling:

Built a Logistic Regression model to predict the top four teams in the Premier League.
Evaluated the model using classification metrics like accuracy, precision, and recall.

Results:

Identified the most influential factors for team success.
Predicted top teams based on current season performance.

Tools:
Web Scraping: Selenium, BeautifulSoup
Data Analysis & Modeling: Pandas, Scikit-learn (Logistic Regression)
Visualization: Matplotlib, Seaborn

Conclusion

Both projects showcase the use of data scraping, preprocessing, analysis, and visualization to derive insights:

The Kenya Airways project reveals customer sentiments and key areas of service improvement.

The Premier League project predicts team performance based on historical and current data.
