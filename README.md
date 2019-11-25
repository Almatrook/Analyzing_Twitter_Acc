
Analyzing and Visualizing WeRateDogs twitter user account 

# Project



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Overview](#overview)
* [Details](#details) 
* [Findings](#findings)
* [Statistical Analysis Scope](#statistical-analysis-scope)
* [Tools](#tools)
* [Installation](#installation)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)


<!-- Overview -->
## Overview
The analysis of tweets from the WeRateDogs account that was gathered and cleaned prior. 
The goal of analyzing is to measure the most popular trends of dog breeds and stages over the time of the account based on the number of retweets and likes.

This project was completed as part of Udacity's Data Analyst Nanodegree certification.


<!-- Detail -->
## Details
twitter-archive-enhanced.csv
	File contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017.
	There are 2356 rows which filtered by tweets with ratings only.
	There are retweet count and favorite count are two of the notable column omissions.
	The ratings probably aren't all correct. Same goes for the dog names and probably dog stages (see below for more information on these) too. You'll need to assess and clean these columns if you want to use them for analysis and visualization.
tweet_json.txt
	Read this file line by line into a pandas DataFrame with (at minimum) tweet ID, retweet count, and favorite count.
twitter_api.py
	This is the Twitter API code to gather some of the required data for the project. Read the code and comments, understand how the code works, then copy and paste it into your notebook.
image-predictions.tsv
	File a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded 
to the most confident prediction (numbered 1 to 4 since tweets can have up to four images).
	File is hosted on Udacity's servers and should be downloaded programmatically using the Requests library


<!-- GETTING STARTED -->
## Findings
Puppos are more popular on average than other stages of the dog. On the contrary, Puppers have lower numbers on average, there are a lot of outliers.
On the table, there are 113 breeds of dog, the most portion of them are not popular.
Based on the top three image predictions, the most common breeds of dog is Golden Retriever and then Labrator Retrievers.
The @dog_rates account was active in 2016 more than in 2015 with almost 50% of all tweets in the database, and then the account activity was decreased by the number of tweets in 2017 with nearly 19%.

<!-- Statistical Analysis Scope -->
## Statistical Analysis Scope
Data wrangling
- Data Gathering
- Data Assessing
- Data Cleaning
- Data visualizations



<!-- Tools -->
## Tools

Python libraries : numpy, pandas, matplotlib, seaborn




<!-- Installation -->
## Installation

1. Clone the repo
```sh
git clone https://github.com/Almatrook/Analyzing_Twitter_Acc
```


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch 
3. Commit your Changes 
4. Push to the Branch 
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under GNU General Public License v3.0. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Abdulbasit Almatrook - abdulbaset.almtrook@gmail.com
Dr. Samad S Kolahi   - skolahi@unitec.ac.nz                     - 