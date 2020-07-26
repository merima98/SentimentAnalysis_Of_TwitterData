# Sentiment Analysis of Twitter data

- Project: "Analysis of the sentiment of Twitter posts", I used for the final work after the first cycle of education at the Faculty of Information Technology Mostar (for obtaining a Bachelor of Information Technology degree).
- The project was written in Python

To work on this project You need to do next steps:

- Install to Anaconda
- Install the Jupyter Notebook through Anaconda cmd, which was used as a project creation environment

- Register a Twitter application to collect the necessary credentials
- Authenticate Python script using API using credentials
- Create the necessary program for analyzing the sentiment of Twitter posts (the project is posted on this repository)

Through creating a project, the user can get acquainted with:
 - PANDAS
 - NLTK
 - Naive Bayes classifier
 - KFold
 - Scikit learn library

- The data used in the paper were collected from Twitter. Initially, the data were unstructured (they contained various modes of expression, frequent repetition of unnecessary characters, etc.). Unstructured data is purified, using the function - creating a specific regex.

- KFold was used in the paper in a ratio of 90:10 (over 90% of the dataset the model was trained, over 10% of the dataset the model was tested). The testing accuracy of the trained model is 68%.