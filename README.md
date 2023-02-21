# MyProjectForGit2

For this project I created a data set detailing the activity of the Wagner Group mercenaries from Twitter API for a school project. 

I went with the Twitter API because it is one of my news sources, and I have always wanted to become familiar with the API. First, I had to figure out how to handle the Twitter API. Based on my initial research, I found there were different methods for calling the Twitter API (with the caveat that some require a fee). I settled on using Tweepy. 

Before I could use Tweepy’s functions, I had to first get Twitter API Keys. The Twitter API keys gave me permission to use Twitter APIs right away. It was trickier to get elevated access, because I had to answer Twitter’s security questions without indicating I was researching a mercenary group. I went back and forth with a representative from Twitter’s developer account before I received elevated access. I then used the POSTMAN tool to test my APIs before coding. 

To write my python script, I utilized python notebook. I found it was easier to use python notebook to test in real time. I started my script by inputting the necessary modules for Tweepy, Pandas, json, csv, datetime, spacy, plotly.express, and spacytextblob. 

It is required to save your API keys in a secure location. The API keys are required for every script in order to use Twitter APIs. The following keys are available in the Twitter developer API portal:

api_key 
api_secrets 
access_token
access_secret 
