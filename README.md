# Sentiment Analysis on Trump Twitter Data

## Project Overview

This project performs sentiment analysis on a dataset of tweets from former U.S. President Donald J. Trump. The objective is to:

- Analyze public sentiment trends over time
- Extract key themes and emotional tone of tweets
- Classify tweets into positive, negative, or neutral sentiment
- Visualize linguistic patterns and political communication strategies

---

## 📄 Dataset Description

| Field Name       | Description                              |
|------------------|------------------------------------------|
| `tweet_id`       | Unique identifier for each tweet         |
| `date`           | Timestamp of the tweet                   |
| `content`        | Raw tweet text                           |
| `retweets`       | Number of retweets                       |
| `favorites`      | Number of likes/favorites                |
| `sentiment`      | Labeled or predicted sentiment category  |

> Dataset sourced from publicly available Trump tweet archives and processed for academic research purposes.

---

##  Technologies Used

| Area                  | Tools & Libraries                     |
|------------------------|----------------------------------------|
| Programming            | Python 3.x                             |
| Text Processing        | NLTK, TextBlob, re                     |
| Visualization          | Matplotlib, WordCloud, Seaborn         |
| Modeling & Sentiment   | TextBlob, VaderSentiment               |
| Notebook Environment   | Jupyter Notebook (.ipynb)              |

---

##  Methodology

1. **Data Cleaning**:
   - Removed URLs, hashtags, mentions, and special characters
   - Converted to lowercase and tokenized

2. **Sentiment Analysis**:
   - Applied **TextBlob** and **VADER** polarity scoring
   - Classified tweets as **Positive**, **Negative**, or **Neutral**

3. **Text Mining**:
   - Generated **word clouds** for each sentiment group
   - Extracted most common terms using `nltk.FreqDist`

4. **Temporal Analysis**:
   - Trendlines of sentiment scores over time
   - Identified spikes during major political events

5. **Engagement Metrics**:
   - Analyzed how sentiment correlates with likes and retweets

---

## Key Insights

- **Negative tweets** received higher engagement on average
- **Political events** (e.g., elections, debates) triggered sentiment spikes
- Common negative terms include "fake", "disaster", "crooked"
- **Positive tweets** often include "great", "thank you", "success"
- Tweets mentioning **opponents** had more polarized sentiment



