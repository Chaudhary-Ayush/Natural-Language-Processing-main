This repository contains the Python code for Extract Tweets using ScraperAPI.

_**Here's what you'll find in this repository:**_

Scrape_Tweets_ScraperAPI.py: This is the main Python code file that extracts tweets using ScraperAPI.

README.md (This File): This file contains information about the project, including setup instructions and usage examples.

_**Project Description** _

This Python code leverages the ScraperAPI to extract tweets containing a specific keyword. It retrieves the first 100 tweets matching the query and saves them in a JSON file.

_**Important Note:**_

To use this code, you'll need a ScraperAPI account and an API key.

_**Setup:**_

**Sign Up for ScraperAPI**: Create an account at https://www.scraperapi.com/ and obtain your API key.

**Install Libraries**: Open your terminal or command prompt and run the following commands to install the required libraries:

pip install requests pandas


_**Configure API Key:**_

Open the Scrape_Tweets_ScraperAPI.py file in a text editor.

Locate the variable named api_key.

Replace the placeholder value with your actual ScraperAPI key obtained in step 1.

_**Usage:**_

Save the Scrape_Tweets_ScraperAPI.py file.

Open your terminal or command prompt and navigate to the directory where you saved the file.

Run the script using the following command:

python Scrape_Tweets_ScraperAPI.py


This will extract the first 100 tweets containing the keyword "viratkohli" (you can modify the 'query' parameter) and save them to a file named "tweets.json". The JSON file will include only the "snippet" and "title" fields of each tweet.
