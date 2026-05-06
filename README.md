# 🎥 YouTube Comments Sentiment Analysis

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red.svg)
![YouTube API](https://img.shields.io/badge/API-YouTube%20Data%20v3-orange)


---

## 🚀 Overview

An end-to-end **YouTube Comments Sentiment Analysis Web App** that extracts comments from any YouTube video and analyzes audience sentiment using NLP techniques.

The application provides **interactive visual insights** along with **channel and video statistics**, helping understand audience engagement effectively.

---

## ✨ Features

* 🔗 Input any YouTube video link
* 📥 Extract comments using YouTube Data API
* 🧠 Perform sentiment analysis (Positive / Negative / Neutral)
* 📊 Interactive visualizations (Bar chart & Pie chart)
* 📺 Display channel & video statistics
* 💾 Download comments as CSV
* 💻 Clean and interactive UI with Streamlit

---

## 🛠️ Tech Stack

| Category      | Tools Used          |
| ------------- | ------------------- |
| Language      | Python              |
| Frontend/UI   | Streamlit           |
| API           | YouTube Data API v3 |
| NLP           | TextBlob            |
| Data Handling | Pandas              |
| Visualization | Plotly              |

---

## ⚙️ System Architecture

```
User Input (YouTube Link)
        ↓
Extract Video ID
        ↓
YouTube Data API (Fetch Comments + Metadata)
        ↓
Store Comments (CSV)
        ↓
Sentiment Analysis (TextBlob)
        ↓
Visualization (Plotly)
        ↓
Display Results (Streamlit UI)
```

---



