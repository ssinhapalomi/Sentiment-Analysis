# Importing necessary libraries
from textblob import TextBlob

# Sample text (can be replaced with your own text)
text = "I love using Python for data analysis. It's fantastic!"

# Performing sentiment analysis
blob = TextBlob(text)
sentiment_score = blob.sentiment.polarity

# Displaying sentiment score
print("Sentiment Score:", sentiment_score)
