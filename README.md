# UDACITY-Data-Scientist-Recommendations_with_IBM
## by Data Camp 442


## Project Overview
For this project I will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles you think they will like.

## My Tasks
### Exploratory Data Analysis
Before making recommendations of any kind, you will need to explore the data you are working with for the project. 

### Rank Based Recommendations
To get started in building recommendations, you will first find the most popular articles simply based on the most interactions. 
Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. 
These are then the articles we might recommend to new users (or anyone depending on what we know about them).

### User-User Based Collaborative Filtering
In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with.
These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. 
You will implement this next.

### Matrix Factorization

Finally, you will complete a machine learning approach to building recommendations. 
Using the user-item interactions, you will build out a matrix decomposition. Using your decomposition, you will get an idea of how well you can predict new articles an individual might interact with (spoiler alert - it isn't great). 
You will finally discuss which methods you might use moving forward, and how you might test how well your recommendations are working for engaging users.

## Content
Recommendations_with_IBM.ipynb - Jupyter Notebook
