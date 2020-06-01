
# IBM Recommendation System

### About : 
I analyzed user behavior and social network data on IBM Watson platform to build a recommendation engine based on to surface content most likely to be relevant to a user. 


<img src="IBM.png">


## Project Motivation

IBM has an online data science community where members can post tutorials, notebooks, articles, and datasets. In this project, I built a recommendation engine based on user behavior and social network data, to surface content most likely to be relevant to a user. I analyzed the interactions that users have with articles on the IBM Watson Studio platform and made different recommendation models to recommend new articles to them. This project consisted of building various types of recommendation engines such as rank-based, user-user collaborative filtering, and matrix factorization.

The project is divided into the following sections:


### I. Exploratory Data Analysis

Before making recommendations of any kind, you will need to explore the data you are working with for the project. Dive in to see what you can find. There are some basic, required questions to be answered about the data you are working with throughout the rest of the notebook. Use this space to explore, before you dive into the details of your recommendation system in the later sections.

### II. Rank Based Recommendations

To get started in building recommendations, you will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

### III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. You will implement this next.

### IV. Content Based Recommendations

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, you might come up with some extremely creative ways to develop a content based recommendation system. You are encouraged to complete a content based recommendation system, but not required to do so to complete this project.

### V. Matrix Factorization

Finally, you will complete a machine learning approach to building recommendations. Using the user-item interactions, you will build out a matrix decomposition. Using your decomposition, you will get an idea of how well you can predict new articles an individual might interact with. You will finally discuss which methods you might use moving forward, and how you might test how well your recommendations are working for engaging users.

### VI. Extras & Concluding

As other work to show off your skills, you can configure your code into a class and deploy your code to a flask app (like in the lessons). Adam will walk you through how he did this on IBM. Alternatively, you could deploy using Heroku. Again, these steps are not required to complete the project, but can help you push your skills and show off your work to the world.

### Files :

1. Recommendations_with_IBM.html : This is the html screenshot of the jupyter notebook 'Recommendations_with_IBM' and contains all the code 
with its output.

2. Recommendations_with_IBM.ipynb : The jupyter notebook where all the coding has been done.

3. project_tests.py : Some tests written to check the answers to the questions in Recommendation_with_IBM.ipynb.

4. top_10.p, top_20.p, top_5.p : Python pickle files for tests used in the notebook.

5. user_item_matrix.p : Python pickle file providing data used in making the recommendation model.


### Installations

This project requires **Python 3.x** and the following Python libraries installed:

- scikit-learn==0.21.2
- pandas==0.24.2
- numpy==1.16.4
- matplotlib==3.1.0

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.


### Data:

The data is for IBM an online data science community through udacity. 

### Licensing, Authors, Acknowledgements

This project is part of Data scientist Nanodegree from udacity.

This work is licensed under a [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nc-nd/4.0/). Please refer to [Udacity Terms of Service](https://www.udacity.com/legal) for further information.

