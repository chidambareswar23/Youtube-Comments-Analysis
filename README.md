# 🎥 YouTube Comments Sentiment Analysis

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red.svg)
![YouTube API](https://img.shields.io/badge/API-YouTube%20Data%20v3-orange)
![License](https://img.shields.io/badge/License-MIT-green.svg)

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

## 📸 Screenshots

### 🔹 Home Interface

![Home](screenshots/home.png)

### 🔹 Sentiment Analysis Results

![Charts](screenshots/charts.png)

### 🔹 Channel & Video Stats

![Stats](screenshots/stats.png)

> 📌 *Add your screenshots inside a `/screenshots` folder in your repo.*

---

## ▶️ Run Locally

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git

# Navigate to project
cd your-repo-name

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
```

---

## 🔑 Setup API Key

1. Get API key from Google Cloud Console
2. Enable **YouTube Data API v3**
3. Add your key in the code:

```python
API_KEY = "YOUR_API_KEY"
```

---

## ⚠️ Limitations

* Sentiment analysis may not handle sarcasm/slang accurately
* CSV storage is not scalable for large datasets
* Dependent on YouTube API quota limits

---

## 🔮 Future Improvements

* 🔥 Use advanced NLP models (BERT / Transformers)
* 🗄️ Replace CSV with database (MongoDB / PostgreSQL)
* ⚡ Add real-time streaming analysis
* 🌐 Multi-language sentiment detection

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Your Name**
📧 [your-email@example.com](mailto:your-email@example.com)
🔗 LinkedIn | GitHub

---

⭐ If you like this project, give it a star!
