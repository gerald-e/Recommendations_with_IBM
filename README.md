# Recommendations with IBM Project

## Table of Contents

1. [Project Motivation](#motivation)
2. [Installation](#installation)
3. [File Descriptions](#files)
4. [Licensing, Authors, and Acknowledgements](#licensing)
5. [Instructions](#instructions)

## Project Motivation<a name="motivation"></a>

Recommend articles for users on the IBM Watson Studio platform using the following techniques:

1. Rank-Based Recommendations: Recommend most popular articles based on the highest user interactions
2. User-User Based Collaborative Filtering: Make a more personal recommendation to a user by recommending unseen articles that were viewed by similar users
3. Content Based Recommendations: Recommend articles that are similar in content to a given article
4. Matrix Factorization: Use SVD to find new articles that a user will like to read

## Installation <a name="installation"></a>

Python standard configuration
* Python 3.5+ (I used Python 3.7)
* Machine Learning Libraries: NumPy, SciPy, Pandas, Sciki-Learn
* Natural Language Process Libraries: NLTK, pickle, re


## File Descriptions <a name="files"></a>

1. data
    - articles_community.csv: dataset including all the community about the articles 
    - user-item-interactions.csv: dataset including all user interactions to the articles
2. root
    - README.md: This file, a description about this project
    - Recommendations_with_IBM.ipynb: Jupiter notebook for Contains the implemented recommendation techniques
    - project_tests.py: routine to give the asserts for all questions in jupyter notebook

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credits must be given to Udacity for the starter codes and IBM for provding the data used by this project. 

* [Udacity](https://www.udacity.com/)
* [IBM] Examples of articles on the IBM Watson Studio Platform

## Instructions<a name="instructions"></a>

Run jupiter notebook