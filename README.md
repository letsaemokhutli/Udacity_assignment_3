# Recommendations With IBM

## Introduction

This project impliments different types of recomendation engines, ranking based, collaboraive based, and ML based, matrix facorizations by analyzing the interactions that users have with articles on the IBM Watson Studio platform and make recommendations to them about new articles they'll like. With skills gained in this project, giving customers bespoke or personalized products  in the context of business

### Motivation

The motivation behind this project is to gain skill in building different types of recommendation engines understand user behavior and provide personalized recommendations to enhance user engagement and satisfaction on the IBM Watson Studio platform.

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

Before making recommendations, we perform an exploratory analysis of the data to understand its structure and establish data facts and insights.

### II. Rank Based Recommendations

Rank based recommendations do their recommendations based on the most popular interactions based in interactions

### III. User-User Based Collaborative Filtering

With collaborative filtering implemented, recommendations of articles done by finding similar users based on their interactions.

### IV. Matrix Factorization

Finally, we explore matrix factorization techniques to build a machine learning approach to recommendations. Which used SVD technique to be optimal and cater for new users without past interactions.

### V How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/restaurant-revenue-prediction.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the capstone_prep_fle.ipnyb using jupyter notebooks:
