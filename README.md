# Overcoming the Language Barrier: American Sentiment Towards South Korean Comedy-Horror Movies

## Final Project for COMM 313: _Computational Text Analysis_ (Spring 2021)

My favorite movies are the ones that take me through a roller coaster of emotions, feeling everything from belly-aching laughter to heavy-hearted tears. The ones that leave me shocked and pensive for days on end. One of the first movies that made me feel all these things was _The Host_ (2006), directed by Bong Joon-Ho. 

Although many people might automatically think _Parasite_ when they hear "Bong Joon-Ho," for me it was _The Host_ because that was my first experience with his work. More than a decade ago when I first watched it, I was still living in Seoul, South Korea. I was struck by the unique storyline, characters, dialogue, and action; every time my family and I drove past the Han River, I was terrified (if you don't get this reference, check out the 2-min trailer [here](https://www.youtube.com/watch?v=1HRTy26s4hw)). I had never seen a comedy-horror film like that before. And every time I rewatch it, it still leaves an impression on me! 

But of course, these are my subjective thoughts and opinions...

I began to wonder what other people thought about Director Bong's earlier films, the ones before his globally successful and acclaimed 2019 film. The questions lingered in my head: **How does the American public rate _Parasite_ compared to _The Host_ ? Is there a difference between how film critics vs. the public have rated these movies?** These questions led me to embark on a journey to figure out how I can use Python data analysis to help answer my questions. 

My primary goal throughout this project is to carry out sentiment analysis using various types of tools/lexicons to analyze 1) critic reviews gathered from the [Nexis Uni](https://www.lexisnexis.com/en-us/professional/academic/nexis-uni.page) database and 2) movie reviews from sites like [Metacritic](https://www.metacritic.com/) and [Rotten Tomatoes](https://www.rottentomatoes.com/). The main question I am hoping to answer is whether or not _Parasite_ has been more well-received than _The Host_ ; that is, more positive ratings, higher sentiment scores, etc. Hopefully, through my project, you will be able to gain a better understanding of the overall American public sentiment towards Director Bong Joon-Ho's two films that I selected (feel free to check out his other movies, too)! 

### Introducing my project folders

Throughout the sub-folders in this project, you will come across the following:

* `data` - This is where you can find all the data that I collected and used: text files (.txt), JSON files, and lexicons I utilized for my sentiment analysis. 
* `data_analysis` - In this folder, you will find individual notebooks in which I carried out data collection (scraping, cleaning, organizing) and data analysis to gain insights about the corpora in my data folder. The analyses include splitting reviews into positive and negative, running keyness analysis, and carrying out sentiment analysis using VADER, NRC Lexicons, and TextBlob.
* `final_data_story` - Here you can access the final product of my research project: a data-driven article I wrote on Medium.com. You will see both the direct link to my story, as well as a PDF version.
* `presentation` - This folder contains a brief mid-progress presentation I gave in my class about this project. It is in the format of a Python Jupyter Hub notebook that contains slides. I used this to present on my research question and hypothesis, data collection, brief initial analysis and results, and further steps to take for finishing up my work.

There you have it! This is only the introductory roadmap through my project. Again, the final product of my research can be found in the `final_data_story` folder. Please make sure to check out the files and text data in the `data` folder, and then follow along with each notebook in the `data_analysis` folders to understand the data collection and data analysis processes I went through before writing my article. 

Thank you so much, and I hope you enjoy! 

Cheers,

Mary