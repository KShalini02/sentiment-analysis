# Sentiment Analysis on Tweets😊

This Python script performs sentiment analysis on tweets using the TextBlob library. It includes data cleaning, preprocessing,
sentiment analysis, and visualization of sentiments.

Sentiment Analysis is the process of ‘computationally’ determining whether a piece of writing is positive, negative or neutral.
It’s also known as opinion mining, deriving the opinion or attitude of a speaker. 

## Sections:

### 1. Import Libraries and Load Data
- The required libraries are imported, including pandas, numpy, seaborn, matplotlib, TextBlob, nltk, and wordcloud.
- The tweets are loaded from a CSV file ('tweets.csv') into a Pandas DataFrame.

### 2. Data Exploration and Cleaning
- Basic information about the DataFrame is printed, including its shape, head, and null values.
- Data cleaning is performed to handle special characters, URLs, mentions, and hashtags.

### 3. Text Preprocessing
- A function `data_processing` is defined to preprocess text data by converting to lowercase, removing URLs, mentions,
and non-alphanumeric characters, tokenizing, and removing stopwords.
- Duplicates are removed from the 'texts' column.

### 4. Sentiment Analysis
- The TextBlob library is used to calculate the sentiment polarity for each tweet.
- Sentiments are categorized as 'Positive', 'Negative', or 'Neutral'.

### 5. Data Visualization
- Seaborn and Matplotlib are used to create count plots and pie charts to visualize the distribution of sentiments.

### 6. Word Clouds
- Word clouds are generated for positive, negative, and neutral tweets to display the most frequent words.

### 7. Additional Sentiment Analysis Function
- An additional function `analyze_sentiment` is defined to categorize comments into sentiments and random categories.

### 8. Example Analysis
- The `analyze_sentiment` function is applied to the first 10 comments from the 'texts' column of the DataFrame to demonstrate sentiment analysis.


