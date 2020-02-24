# MBC-MASR-Youtube-Channel-Mining
## Mining YouTube Data
This report contains the Mining YouTube Data using Python project as part of my data science task .
There are two parts in this project: The first part - About YouTube is an introduction of YouTube,
its history and some interesting statistics. The second part - Mining YouTube Data using Python contains the Python code to work with
YouTube Data API in order to extract data and perform various analysis on YouTube videos.

### The Process
In this project, I have used YouTube Data API v3 to extract data about videos and retrieve their statistics such as number of views, likes, dislikes, comments, etc. 
Then I converted these statistics into pandas DataFrame for further analysis.
Analysis performed included ranking the most popular videos by view count and like count, and analyzing view count by day of the week.
In the last part of this project, I have also extracted the comments from a YouTube video and performed wordcloud visualization on the most popular words, and followed by sentiment analysis using NLTK (the Natural Language Toolkit, or more commonly NLTK, is a suite of libraries and programs for symbolic and statistical natural language processing for English written in the Python programming language).

### In this project, I have used YouTube Data API v3 to extract data about videos and retrieve their statistics such as number of views, likes, dislikes, comments, etc. Then I converted these statistics into pandas DataFrame for further analysis. Analysis performed included ranking the most popular videos by view count and like count, and analyzing view count by day of the week. In the last part of this project, I have also extracted the comments from a YouTube video and performed wordcloud visualization on the most popular words, and followed by sentiment analysis using NLTK. The Natural Language Toolkit, or more commonly NLTK, is a suite of libraries and programs for symbolic and statistical natural language processing for English written in the Python programming language.


Note: To use the YouTube Data API, you will need a API key which you can obtain in the Google APIs Console. You will need to create a new project, and enable the YouTube Data API for the project. To simplify things, I have used Google API python client which is a python client to interact with the Google APIs in an easier way. In order to use the API, you have to build a resource object for that API. 
