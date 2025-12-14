# 🎬 Movie Recommendation System

A **content-based movie recommendation system** that suggests similar movies based on a user’s selected movie. The system analyzes movie features such as **overview, genres, cast, and crew** and uses **cosine similarity** to generate recommendations. An interactive **Streamlit web app** displays recommended movies along with their posters fetched from the **TMDB API**.

---

## 🚀 Features

- Content-based movie recommendations
- Cosine similarity for finding similar movies
- Interactive Streamlit web interface
- Real-time movie poster fetching using TMDB API
- Clean and modular project structure
- Ready for deployment (Streamlit Cloud / HuggingFace)

---

## 🧠 How It Works

1. Movie metadata is preprocessed (overview, genres, cast, crew)
2. Text features are converted into vectors
3. Cosine similarity is calculated between movies
4. When a user selects a movie, the system recommends the **top 5 similar movies**
5. Movie posters are fetched dynamically using the TMDB API

---

## 🛠 Tech Stack

- **Python**
- **Pandas & NumPy**
- **Scikit-learn**
- **Streamlit**
- **TMDB API**

---

##Link: https://sayedfaisalshah12-movie-recommended-system-app-liawmb.streamlit.app/

--

## 📂 Project Structure

```text
Movie-Recommender-System/
│
├── app.py
├── requirements.txt
├── README.md
├── model/
│   ├── movie_list.pkl
│   └── similarity.pkl
├── dataset/
│   ├── tmdb_5000_movies.csv
│   └── tmdb_5000_credits.csv
├── .env
└── .gitignore
