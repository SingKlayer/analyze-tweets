# Twitter sentiment analyzer

## Sentiment Analysis Tool with Tweepy and TextBlob

This Python script analyzes the sentiment of tweets and generates a sentiment plot. It utilizes the Tweepy library to access Twitter data and TextBlob for sentiment analysis.

**Note:** The original source on gist.github.com is no longer available. This README serves as a replacement.

## Getting Started

This guide will help you set up and run the project locally for development and testing.

### Prerequisites

Before proceeding, ensure you have the following software installed:

* Python 3.x ([https://www.python.org/downloads/](https://www.python.org/downloads/))
* Tweepy library (`pip install tweepy`)
* TextBlob library (`pip install textblob`)
* Matplotlib library (`pip install matplotlib`)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/SingKlayer/analyze-tweets.git
   ```

2. **Create a `keys.txt` file:**

   - In the project directory, create a file named `keys.txt`.
   - Paste your Twitter API credentials (obtained from [https://developer.twitter.com/en](https://developer.twitter.com/en)) into the file, each on a separate line:

     ```
     <bearer_token>
     <consumer_key>
     <consumer_secret>
     <access_token>
     <access_token_secret>
     ```

### Running the Script

1. **Navigate to the project directory:**

   ```bash
   cd sentiment-analysis-tool
   ```

2. **Run the script:**

   ```bash
   python bot_twitter.py
   ```

This will:

* Analyze the sentiment of the provided sample tweets.
* Generate a sentiment plot (`sentiment_plot.png`).
* Upload the plot to Twitter and post a tweet with the analysis.

**Note:** Replace the sample tweets with your desired search query or method to obtain tweets for analysis.

## Additional Notes

* This script demonstrates a basic example of sentiment analysis using Tweepy and TextBlob.
* For more advanced usage, refer to the respective library documentations.

## Warning:

* Due to the new Twitter API, some End-Points and Functions may not work as intended. Feel free to fork and adapt the code.

## Leave a star to support <3
