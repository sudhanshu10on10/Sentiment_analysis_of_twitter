# Twitter Sentiment Analysis

A Python script that analyzes the sentiment of tweets using a lexicon-based approach, classifying them as positive or negative based on predefined word lists.

## How It Works
- Reads tweet data from a CSV file
- Strips punctuation and normalizes text
- Matches words against positive and negative word lexicons
- Outputs sentiment scores for each tweet to a new CSV

## Output
Generates `resulting_data.csv` with the following columns:
- `Number of Retweets`
- `Number of Replies`
- `Positive Score`
- `Negative Score`
- `Net Score`

## Files
- `project_twitter_data.csv` — Input tweet data
- `positive_words.txt` — Lexicon of positive words
- `negative_words.txt` — Lexicon of negative words
- `resulting_data.csv` — Output sentiment results

## Tech Stack
- Python
- CSV file handling
- Lexicon-based sentiment scoring

## Run Locally
```bash
python sentiment_analysis.py
```
