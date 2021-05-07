# Data analysis notebooks for COMM313 _Computational Text Analysis_ Final Project

Hello again! In this folder, I will be providing an overview to lead you through all the Jupyter notebooks I created to help answer my main question of whether _Parasite_ has been more well-received than _The Host_ both by film critics and the public audience. Each of the notebooks generally go under three themes: 1) analysis, 2) data collection, and 3) set-up/functions. 

**Note:** It probably makes most sense to go through the data collection notebooks BEFORE looking at the analysis notebooks! It is organized in the following order because of alphabetical ordering.

## Analysis notebooks:

* `analysis_critic_nexis` - In this notebook, I go through the critic reviews downloaded from Nexis Uni and run sentiment analysis using VADER. I discuss limitations of this analysis and also carry out some word and n-gram frequency analysis to gain a better understanding of what kind of language is used throughout the critic reviews.
* `analysis_user_metacritic` - Throughout this notebook, I carry out four parts of analyses on the user reviews I scraped and organized from Metacritic. I divide up the reviews into positive and negative reviews (by rating), and run sentiment analysis using various tools/lexicons including VADER, NRC VAD, and NRC Emotion Lexicon. 
* `analysis_user_tomatoes1` - In this notebook (pt. 1 of a 2-part series), I run two parts of analyses on the user reviews I scraped and organized from Rotten Tomatoes. I focus primarily on splitting up my reviews into positive and negative, just like in the previous notebook, and then explore specific words or phrases occurring frequently across the reviews. I also focus on Keyness analysis, KWIC concordance analysis, to gain a better understanding of which words occur most frequently for positive and negative reviews.
* `analysis_user_tomatoes2` - This notebook is continued from the previous one, and in here I run the rest of my analyses on user reviews from Rotten Tomatoes: sentiment analysis using VADER, NRC VAD & NRC Emotion Lexicons. I then spend the rest of this notebook exploring ways to display and visualize my results, and see which ones would be most useful for my data story.
* `trying_TextBlob_SA` - In this notebook, I investigate using TextBlob instead of VADER to analyze the sentiment of the Nexis Uni critic reviews. I look at polarity, subjectivity, and classification of sentiment across the critic reviews, and compare them to the VADER results from earlier.

## Data collection notebooks:

* `lang_detect` - This notebook runs through the steps I took to use a language detector tool for filtering out non-English movie reviews from my corpora, since my project focuses on American, English reviews of the two movies.
* `metacritic_host_user` - In this notebook, I work on web-scraping and cleaning user reviews of The Host that originated from Metacritic. I carry out initial analyses on the reviews, such as frequency analysis and looking to see what types of sentiment analysis I can use on the data. I also attempt to scrape some critic reviews from Metacritic.
* `metacritic_parasite_user` - In this notebook, I carry out similar steps as the previous one for web-scraping Metacritic user reviews of Parasite. I also attempt to gather the critic reviews.
* `nexis_host_critic` - In this notebook, I load in the Nexis Uni critic review (of The Host) documents that I downloaded, and process the texts so I can use them in my analysis notebooks. I work on extracting the body text of these reviews, and then writing it out as a new JSON file so I can analyze the data.
* `nexis_parasite_critic` - Here, I load in the critic reviews of Parasite that I downloaded from Nexis Uni, and similar to the previous notebook, I process the texts and extract the body text. Then I save the cleaned, organized file out as a new JSON file so I can analyze it in another notebook.
* `tomatoes_host_user` - In this notebook, I web-scrape user (audience) reviews of The Host from the Rotten Tomatoes website, and adapt a code to extract those reviews. I then save the text data out as a new JSON file, on which I can run analyses in the other notebooks.
* `tomatoes_parasite_user` - In this notebook, I carry out similar steps from above: I web-scrape user reviews of Parasite from Rotten Tomatoes and extract the reviews using an adapted code (credit is given in the notebook), and save this out as a new JSON file so that I can work on it in the analysis notebooks.

## Set-up, functions notebook:

* `functions` - This notebook contains all the functions I use throughout my `data_analysis` notebooks.