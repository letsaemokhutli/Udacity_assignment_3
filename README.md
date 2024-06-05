# Recommendations With IBM

## Introduction

In this project, we analyze the interactions that users have with articles on the IBM Watson Studio platform and make recommendations to them about new articles they'll like.

### Motivation

The motivation behind this project is to understand user behavior and provide personalized recommendations to enhance user engagement and satisfaction on the IBM Watson Studio platform.

## Libraries Used

- Python 3.7 and above
- pandas
- numpy
- matplotlib
- pickle
- re
- nltk
- sklearn
- jupyter

## Data

The project uses two CSV files:

1. `user-item-interactions.csv`: Interactions between users and articles.
2. `articles_community.csv`: Contents of articles.

## Overview

The project is structured as follows:

### I. Exploratory Data Analysis (EDA)

Before making recommendations, we perform an exploratory analysis of the data to understand its structure, identify patterns, and gather insights.

### II. Rank Based Recommendations

We start by recommending the most popular articles based on the most interactions. This serves as a baseline recommendation system.

### III. User-User Based Collaborative Filtering

We implement collaborative filtering to recommend articles by finding similar users based on their interactions.

### IV. Content Based Recommendations (Optional)

We explore content-based recommendations by analyzing the textual content of articles and recommending similar articles based on content similarity.

### V. Matrix Factorization

Finally, we explore matrix factorization techniques to build a machine learning approach to recommendations.

## Reference

The dataset is provided by Udacity as part of the Data Scientist Nanodegree program.
