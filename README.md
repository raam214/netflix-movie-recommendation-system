# 🎬 netflix-movie-recommendation-system

A **Netflix-style content-based movie recommendation system** built using **Machine Learning, NLP, and Streamlit**, designed as a **production-ready portfolio project**.

🔗 **Live App**: https://ai-movie-recommendation-system-214.streamlit.app/

---

## 🚀 Features

- 🎥 Content-based movie recommendations
- 🧠 NLP-based similarity using CountVectorizer & Cosine Similarity
- 🖼 Movie posters fetched using TMDB API
- 🎬 Play Trailer button (YouTube)
- ▶ Watch Options redirect (Netflix / Prime / Hotstar via TMDB)
- 📱 Mobile-friendly responsive UI
- ☁️ Deployed on Streamlit Cloud (no large model files)

---

## 🧠 How It Works

1. Movie metadata (genres, keywords, cast, crew, overview) is processed
2. Text data is converted into vectors using **CountVectorizer**
3. **Cosine similarity** finds movies with similar content
4. Recommendations are generated dynamically in memory
5. TMDB API is used for posters, trailers, and watch availability

---

## 🛠 Tech Stack

- **Language**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn  
- **Web Framework**: Streamlit  
- **API**: TMDB (The Movie Database)  
- **Deployment**: Streamlit Cloud  

---

## 📂 Project Structure

ai-movie-recommendation-system/
│
├── app.py
├── requirements.txt
├── README.md
├── data/
│ ├── tmdb_5000_movies.csv
│ └── tmdb_5000_credits.csv
├── assets/
│ └── background.jpg
└── notebooks/
└── eda_and_model.ipynb
