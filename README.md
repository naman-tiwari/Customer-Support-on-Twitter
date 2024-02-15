# Customer-Support-on-Twitter
--------------------------------
**Dataset** https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter/data
# Customer Support for Twitter: Sequence to Sequence Mapping, Emoji Removal, Punctuation Stripping, URL Filtering

This dataset contains a collection of tweets related to customer support on Twitter, where I have performed sequence to sequence mapping, emoji removal, punctuation stripping, and URL filtering.(more processing to follow)

## Dataset Overview

- **Number of Tweets**: 100,000
- **Time Period**: June 2016 to present
- **Data Source**: Twitter Stream API
- **Preprocessing**:
  - Emoji removal
  - Punctuation stripping
  - URL filtering
  - Misspelling correction
  - Removal of retweet symbols

## Data Preprocessing

Our preprocessing steps are based on the work of [1] and [2].

1. **Emoji Removal**: We used a list of 1624 emojis defined by the Unicode v6.0 Standard to remove emojis from the tweets.
2. **Punctuation Stripping**: We removed punctuation marks to simplify the text and make it easier to analyze.
3. **URL Filtering**: We filtered out URLs to reduce noise and focus on the text content.
4. **Misspelling Correction**: We used a dictionary of common misspellings to correct misspelled words.
5. **Removal of Retweet Symbols**: We removed retweet symbols to focus on original tweets.

## Data Usage

This dataset can be used for various natural language processing tasks, such as:

- Sentiment analysis
- Topic modeling
- Sequence to sequence mapping
- Emoji usage analysis

_More Data Preprocessing to follow...._
