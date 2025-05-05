# Twitter Sentiment Analysis

This project performs real-time sentiment analysis on Twitter data using Python. It collects tweets via the Twitter API, cleans and processes the text data, and classifies sentiments (positive, negative, neutral) using NLP techniques and visualization tools.

## 📌 Features

- Real-time tweet extraction using Tweepy
- Text preprocessing (cleaning, tokenization, stopword removal, etc.)
- Sentiment classification using TextBlob
- Visual representation of sentiment distribution
- Word cloud generation for positive and negative tweets

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Libraries Used:**
  - `Tweepy` – for accessing Twitter API
  - `TextBlob` – for sentiment analysis
  - `matplotlib` & `seaborn` – for data visualization
  - `wordcloud` – to generate word clouds
  - `pandas`, `numpy` – for data manipulation
  - `re` – for regex-based text cleaning

## 🚀 Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/Twitter_Sentiment_Analysis.git
   cd Twitter_Sentiment_Analysis
Install Dependencies
Make sure you have Python 3.8 or later. Then run:

bash
Copy
Edit
pip install -r requirements.txt
Set up Twitter API credentials
Create a .env file or use a config section in your notebook with the following variables:

env
Copy
Edit
CONSUMER_KEY=your_consumer_key
CONSUMER_SECRET=your_consumer_secret
ACCESS_TOKEN=your_access_token
ACCESS_TOKEN_SECRET=your_access_token_secret
Run the Notebook
Open the Twitter_Sentiment_Analysis.ipynb in Jupyter or VS Code and execute the cells in order.

📊 Outputs
Pie chart showing sentiment distribution

Bar graph of sentiment counts

Word clouds for positive and negative tweets
