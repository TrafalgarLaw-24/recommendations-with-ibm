# Recommendations with IBM
This project analyzes the interactions that users have with articles on the IBM Watson Studio and make recommendations to them about new articles that they might like.

This project is divided into the following tasks

I. Exploratory Data Analysis

Find out the distribution of articles an user interacts within the dataset and provide a visual and descriptive statistics.


II. Rank Based Recommendations

Provide two functions to get n number of top articles names and n number of top articles ids.


III. User-User Based Collaborative Filtering
Function `create_user_item_matrix`: reformat the df dataframe to be shaped with users as the rows and articles as the columns.
* Each user should appear once in each row.
* Each article should show up in one column only.
* If a user has interacted with an article, then place 1 where the user-row meets for that article-column. It doesn't matter the number of times a user has interacted with the article, all entries where a user has interacted with an article should be a 1.
* If a user has not interacted with an item, then place zero where the user-row meets for that article-column


V. Matrix Factorization
Built using matrix factorization to make article recommendations to the users on the IBM Watson Studio platform

## Content
  * project tests.py
  * Recommendations with IBM ipynb file


## About

  * Created this project as part of the Udacity Data Scientist Nanodegree programme.
