# is434

# Youtube Link
https://www.youtube.com/watch?v=Xd9w1ZMwaz4

# Twitter

## 1. Text Co-occurence
- IPYNB - Python code to find frequency of word pairs, create Networkx graphs and save graph to GML file
- GML files - GML files for 4 tweet groups (Creator&Media, General, Compilers, Vogue Singapore)
- Gephi files - Gephi visualisations from above GML files (Creator&Media, General, Compilers, Vogue Singapore)
  - Gephi Filters - Use the below values for each Gephi file to Filter by Degree Range:
    - Compiler - 16
    - Vogue - 6 
    - Creator/Media - 16
    - General - 87

## 2. Sentiment Analysis
- IPYNB - Python code to process tweets, find sentiment for each tweet and create a trained model based on tweets which can predict the sentiment for an unseen tweet
- sav files - Trained model files
- CSV files - files with original tweets, processed tweet, tokenized tweet and sentiment

## 3. Topic Modelling
- Topic Modelling IPYNB - Python code to process tweets, run multiple LDA models of different topic numbers, find the right topic number, label each tweet with dominant topic
- topics_labelled files - files with processed tweets and topic labels for each Twitter user group
- topics_reptext files - files with topics and representative text for each Twitter user group
- Wordcloud images - Wordclouds of the top words for each topics for each Twitter user group
- TOPICS_LABELLED_FINAL - files including original/processes/tokenised tweets, dominant topics and % contributed, sentiment class and % sentiment
- Topic Sentiment IPYNB - Python code to create TOPICS_LABELLED_FINAL files
- Topic Sentiment Analysis Power BI - Power BI visualisation to see breakdown of sentiment per topic

## 4. Twitter Scraping & Pre-processing
- IPYNB files - Python code to scrape and pre-process twitter data

## 5. Data Folders
- raw twitter data - files containing scraped twitter data
- processed twitter data - filed containing pre-processed twitter data
