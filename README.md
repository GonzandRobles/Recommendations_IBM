# Recommendations with IBM
Udacity Recommendations with IBM project

# Introduction
For this project you will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles you think they will like. 

# Project Tasks

The project will be divided into the following tasks

I. Exploratory Data Analysis

Exploring data, checking for duplicated values, null values, cleaning columns, checking for dimensions of both datasets.

II. Rank Based Recommendations

To get started in building recommendations, you will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. You will implement this next.


IV. Matrix Factorization

Finally, you will complete a machine learning approach to building recommendations. Using the user-item interactions, you will build out a matrix decomposition. Using your decomposition, you will get an idea of how well you can predict new articles an individual might interact with (spoiler alert - it isn't great). You will finally discuss which methods you might use moving forward, and how you might test how well your recommendations are working for engaging users.

# Files

* data = this folder contains the article_community.csv and the user-item-interactions.cvs

* Recommendations_with_IBM.ipynb = contains the project divided by the **Project Tasks** specified above

* user_item_matrix.csv = csv file containing the user & item matrix

* Recommendations_with_IBM.html = html of the ipynb 

