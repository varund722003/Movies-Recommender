🎬 Movie Recommender System

A content-based movie recommender system built using **Python**, **Streamlit**, and **TMDB API**. It suggests movies similar to a selected one and displays their posters using The Movie Database.


---

🚀 Features

- Recommends 5 similar movies based on cosine similarity
- Fetches movie posters using the TMDB API
- Netflix-inspired dark UI
- Deployable on [Render](https://render.com) or run locally

---

## 🧠 How It Works

- Uses a preprocessed `movies.pkl` containing:
  - Movie titles
  - TMDB IDs
- `similarity.pkl` contains a cosine similarity matrix between movies (e.g., from TF-IDF or count vectors)
- Streamlit frontend allows selection and displays recommendations with posters

---

## 🛠️ Project Structure
📁 Movie-Recommender-System/
│
├── app.py # Main Streamlit app
├── movies.pkl # Preprocessed movie metadata
├── similarity.pkl # Precomputed similarity matrix
├── requirements.txt # Python dependencies
├── setup.sh # Startup script for Render
├── Procfile # Render deployment file
└── .gitignore


🧠 Requirements
Python 3.7–3.11

Streamlit

Pandas, NumPy, Requests, scikit-learn

🙋‍♂️ Author
Made with ❤️ by Varun Dandriyal

