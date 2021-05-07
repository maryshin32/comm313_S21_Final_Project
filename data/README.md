# Data files for COMM313 _Computational Text Analysis_ Final Project

Hello hello! This `data` folder contains the data files I use in my analysis notebooks. I divided the data files into three separate sub-folders: `critic_reviews` contains the text files (.txt) I downloaded from [Nexis Uni](https://www.lexisnexis.com/en-us/professional/academic/nexis-uni.page) as well as the JSON files I wrote out after cleaning and organizing them, `lexicons` contains the NRC VAD lexicon and NRC Emotion Lexicon which are two of the tools I used for sentiment analysis, and `user_reviews` has all the JSON files I wrote out after scraping, cleaning, and organizing publicly posted reviews from [Metacritic](https://www.metacritic.com/) and [Rotten Tomatoes](https://www.rottentomatoes.com/). Below, you can find the list of all my data files along with a brief description to introduce you to each of them.
    
## My data files: 

### Critic Reviews
* `sep_docs` - This sub-folder contains the individual documents that I downloaded from Nexis Uni. Each document represents a critic review, whether it's from a newspaper/blog/magazine article, of _Parasite_ or _The Host_ .
* `nexis_host_critic.json` - This JSON file is a list of dictionaries that I wrote out after cleaning and organizing the text files, with each dictionary unit representing the extracted text of an individual critic review of _The Host_ ; there are 27 total critic reviews in this file.
* `nexis_host_critic.txt` - This is a text file containing all 27 of the critic reviews of _The Host_ that I downloaded in bulk from Nexis Uni.
* `nexis_parasite_critic.json` - This is a JSON file I wrote out that contains a list of dictionaries, with each dictionary unit representing the extracted text of an individual critic review of _Parasite_ ; there are 261 total critic reviews in this file.
* `nexis_parasite_critic1.txt` through `nexis_parasite_critic3.txt` - The critic reviews of _Parasite_ that I downloaded from Nexis Uni are divided among these three text files.

### Lexicons
* `NRC-VAD-Lexicon.txt` - This text file represents the NRC Valence, Arousal, and Dominance (VAD) Lexicon, which includes a list of more than 20,000 English words and their valence, arousal, and dominance scores. 
* `NRC_emotion_lexicon.json` - This file includes the NRC Emotion Lexicon, a list of more than 14,000 English words and their associations with eight basic emotions (anger, fear, anticipation, trust, surprise, sadness, joy, and disgust) and two sentiments (negative and positive).

### User Reviews
* `metacritic_host_user.json` - This data file is the JSON file I wrote out after web-scraping, cleaning, and organizing the user reviews of _The Host_ taken from Metacritic. It contains 71 user reviews, after I filtered by year to only include reviews posted between 2007 and 2009, and also took out non-English reviews.
* `metacritic_parasite_user.json` - This data file is the JSON file I wrote out after scraping, cleaning, and organizing user reviews of _Parasite_ from Metacritic. It includes 290 reviews, after I took out non-English ones.
* `tomatoes_host_user.json` - This data file is the JSON file I wrote out after scraping Rotten Tomatoes audience reviews of _The Host_ and filtering by year to only include reviews written in English that were posted between 2007 and 2009. It contains 4,855 reviews.
* `tomatoes_parasite_user.json` - This data file has 4,409 audience reviews of _Parasite_ that I scraped and extracted from Rotten Tomatoes. This includes only English reviews. 