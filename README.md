# COVID-19-Tweets
Explore the COVID-19 tweets, analyse the geographical distribution and the sentiment in tweets

# Project Overview
In this project we are using a tweet dataset has been collected using Twitter API and a Python script. A query for this high-frequency hashtag (#covid19) is run on a daily basis for a certain time period, to collect a larger number of tweets samples.
The collection script can be found here: https://github.com/gabrielpreda/covid-19-tweets
The tweets have #covid19 hashtag. Collection started on 25/7/2020, with an initial 17k batch and will continue on a daily basis.

# Sneekpeek into Key Insights:
Plotted a heatmap to see geographical distribution of tweets using Folium library
![Tweets Concentration Heatmap](https://github.com/ArushiC/COVID-19-Tweets-Analysis/tree/master/Images/heatmap.pmg?raw=true)

Identified sentiments using NLTK Vader library
![Sentiment Distribution](/Images/pie.pmg?raw=true)

Extracted entities from tweets and created a wordcloud
![Entities Wordcloud](/Images/wordcloud.pmg?raw=true)

# Install
This project requires Python 3.6 and the following Python libraries installed:

NumPy
Pandas
Matplotlib
NLTK
You will also need to have software installed to run and execute a Jupyter Notebook

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included. Make sure that you select Python 3.x installer.

# Licensing and Acknowledgements
Thanks to Kaggle for providing access to the data used in this project.
