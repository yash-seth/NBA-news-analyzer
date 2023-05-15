# NBA News Analyzer
## About
NLP techniques applied to real-time NBA news about players

## Modules
### Web Crawler
This modules scraps [Fox Sports News](https://www.foxsports.com/nba/player-news) to get real-time NBA news. These news articles are then passed on to the Natural Language Processing Modules for extraction of additional insights and analysis.

### Natural Language Processing (NLP)
This module applies the following NLP techniques on the gathered news articles for the generation of additional insights and analysis:
- Sentiment Analysis
- Keyword Extraction
- Summarization
- Question Answering
     
The obtained results are then exported as a .csv file, such that they can be easily fed to modules that display it or do futher operating on the generated insights and analysis.

### Frontend
A website is built to display the generated insights and analysis in an easy to consume manner. Below are some demo screenshots:
![image](https://github.com/yash-seth/NBA-news-analyzer/assets/71393551/ff7b9d75-5b25-4443-a73a-29cefe99f720)
![image](https://github.com/yash-seth/NBA-news-analyzer/assets/71393551/23253494-51b8-47f1-8c27-3fbd3f1ed007)

## Technology
- YAKE - Yet Another Keyword Extractor
- Transformers by Hugging Face

