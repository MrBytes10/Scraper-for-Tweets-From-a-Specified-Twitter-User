# Twitter User Timeline Retrieval

This Python script uses the Tweepy library to retrieve the most recent tweets from a specified Twitter user and stores the tweet data in a pandas DataFrame.

## Requirements

- Python 3.x
- Tweepy library
- Pandas library

## Usage

1. Install the required libraries:
2. Obtain your Twitter API credentials (consumer key, consumer secret, access token, and access token secret) from the Twitter Developer Portal.

3. Replace the placeholders in the script with your actual API credentials.

4. Specify the Twitter username and the number of tweets to retrieve by modifying the `username` and `no_of_tweets` variables, respectively.

5. Run the script:
   The script will retrieve the specified number of tweets from the given user's timeline and store the following information in a pandas DataFrame:

- Date Created: The timestamp when the tweet was created
- Number of Likes: The number of likes the tweet received
- Source of Tweet: The source application used to post the tweet
- Tweet: The text content of the tweet

The DataFrame will be printed to the console.

## Note

This script is for demonstration purposes only. It does not include error handling or additional functionalities such as saving the DataFrame to a file or further processing the data.
