# tasks_asked_to_ChatGPT
Analysis of the tasks asked to ChatGPT by Twitter users

Repository containing the files related to the tasks extraction from tweets discussing ChatGPT.
The objective is collecting the actions that users have asked to the OpenAI's chatbot and then reported in tweets.
The extraction is performed through a Rule-Based Named Entity Recognition process. It can be replicated by executing
the Python Notebook named ChatGPT_tasls_extraction.ipynb (note that the path to the input .csv file should be update 
in order to run the script). 

The input data of the project is a dataset of tweets collected through Twitter API. Due to the Twitter's Term and Condition
we are not allowed to publish the texts of the tweets. Therefore, we publish just the Tweets_IDs in the file named chatgpt_dehydrated_tweets.csv.
To retrieve the text of the tweets and perform the analysis, the Tweets_IDs should be hydrated first.
