# Enhancing Content Creation Using YouTube Comments Sentiment Analysis
This project is an end-to-end data analysis application that extracts YouTube video comments and performs sentiment analysis to derive meaningful insights about audience engagement.

The system is built using Python and integrates the YouTube Data API to fetch real-time data. It processes user comments using Natural Language Processing (NLP) techniques and visualizes the results through an interactive dashboard.

🚀 Features
🔗 Accepts any YouTube video link as input
📥 Extracts comments using YouTube Data API
🧹 Cleans and stores comments in CSV format
🧠 Performs sentiment analysis (Positive, Negative, Neutral)
📊 Displays results using interactive charts (Bar & Pie)
📺 Shows channel and video statistics (views, likes, subscribers)
💻 User-friendly interface built with Streamlit

🛠️ Tech Stack
Python
Streamlit – Web application framework
YouTube Data API v3 – Data extraction
TextBlob – Sentiment analysis
Pandas – Data processing
Plotly – Data visualization

⚙️ How It Works
User inputs a YouTube video link
The system extracts the video ID
Comments are fetched using YouTube API
Data is stored in a CSV file
Sentiment analysis is performed using TextBlob
Results are visualized using interactive charts
Channel and video metadata are displayed

📸 Output
Sentiment distribution (Positive / Negative / Neutral)
Bar chart and pie chart visualizations
Channel information and video statistics

⚠️ Limitations
Sentiment analysis is based on TextBlob (limited accuracy for sarcasm/slang)
Uses CSV storage (not scalable for very large datasets)
Depends on YouTube API quota limits
