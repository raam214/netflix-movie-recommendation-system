# 🎬 AI Movie Recommendation System

> Netflix-style content-based movie recommender using NLP, TF-IDF & Cosine Similarity — powered by TMDB API

[![Live App](https://img.shields.io/badge/Live%20App-Streamlit-FF4B4B?style=for-the-badge&logo=streamlit)](https://ai-movie-recommendation-system-214.streamlit.app)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python)](https://python.org)
[![TMDB](https://img.shields.io/badge/TMDB-API-01D277?style=for-the-badge)](https://themoviedb.org)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-F7931E?style=for-the-badge&logo=scikit-learn)](https://scikit-learn.org)

---

## 🚀 What It Does

Enter any movie title → get instant AI-powered recommendations with posters, trailers & watch options:

- 🎥 **Content-Based Filtering** — recommends movies by genre, cast, crew & keywords
- 🧠 **NLP Pipeline** — TF-IDF vectorization + Cosine Similarity scoring
- 🖼 **Movie Posters** — fetched live from TMDB API
- 🎬 **Play Trailer** — direct YouTube trailer links
- ▶ **Watch Options** — Netflix / Prime / Hotstar via TMDB
- 📱 **Responsive UI** — mobile-friendly Streamlit interface

---

## 🧠 How It Works

1. Movie metadata (genres, keywords, cast, crew, overview) is preprocessed
2. Text features are combined into a single content string
3. **TF-IDF Vectorizer** converts text into numerical vectors
4. **Cosine Similarity** computes pairwise movie similarity scores
5. Top-N similar movies are returned with live TMDB poster & trailer data

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Language | Python 3.x |
| ML / NLP | Scikit-learn, TF-IDF, Cosine Similarity |
| Data Processing | Pandas, NumPy |
| Frontend | Streamlit |
| API | TMDB (The Movie Database) |
| Deployment | Streamlit Cloud |

---

## ⚙️ Run Locally
```bash
# Clone the repo
git clone https://github.com/raam214/netflix-movie-recommendation-system
cd netflix-movie-recommendation-system

# Install dependencies
pip install -r requirements.txt

# Add your TMDB API key
# Create .env file and add:
# TMDB_API_KEY=your_key_here

# Run
streamlit run app.py
```

---

## 🔑 Get Free TMDB API Key

1. Go to [themoviedb.org](https://www.themoviedb.org)
2. Sign up for free
3. Settings → API → Create API Key
4. Add to `.env` file

---

## 📁 Project Structure
```
netflix-movie-recommendation-system/
├── app.py                    # Main Streamlit app
├── requirements.txt          # Dependencies
├── README.md                 # This file
├── data/
│   ├── tmdb_5000_movies.csv
│   └── tmdb_5000_credits.csv
├── assets/
│   └── background.jpg
└── notebooks/
    └── eda_and_model.ipynb
```

---

Built by **Ram Dukare** · Powered by TMDB API · Scikit-learn · Streamlit
