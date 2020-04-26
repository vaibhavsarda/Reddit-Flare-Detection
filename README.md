# Reddit-Flare-Detection
This project is on building a classifier for detecting flairs of Reddit posts.
The classifier in this project is trained to predict the following Reddit flairs:
1. Scheduled
2. Politics
3. Photography
4. Police/Economy
5. AskIndia
6. Sports
7. Non-Political
8. Science/Technology
9. Food
10. Business/Finance
11. Coronavirus
12. Unverified

### REQUIREMENTS
Following Python modules are required to be installed:

1. praw (pip install praw)
2. pandas (pip install pandas)
3. nltk (pip install nltk)
4. wordcloud (pip install wordcloud)
5. matplotlib (pip install matplotlib)
6. sklearn (pip install sklearn)
7. pickle (pip install pickle)

### REPRODUCING DEVELOPMENT ENVIRONMENT AND CODE
##### (a) Reproducing Results
To reproduce the results in the Reddit Flare Detection.ipynb file, follow these steps:
1. Download the dataset file "Reddit_data_limit_50.csv" in this repository.
2. Specify the path to the downloaded file in step 1 in the first code cell of Exporatory Data Analysis (EDA). 
3. Except for code cells in Part I (Reddit Data Collection), run all code cells to reproduce results.

##### (b) Collecting Reddit data and then training a classifier
To collect your own data from Reddit and then train a classifier over it, follow these steps:
1. To collect latest reddit data, create an account on Reddit.
2. In the first code cell under Part I (Reddit Data Collection), enter the values of client_id, client_secret, user_agent, username and password parameters.
3. Now, execute all code cells to obtain the results on your own dataset collected from Reddit.
