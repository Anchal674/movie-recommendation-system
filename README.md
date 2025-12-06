# 🎬 movie-recommendation-system
 
 A machine learning–based Movie Recommendation System built using Python.
 The system recommends movies to users based on content similarity (genre, cast, keywords, overview, etc.)  using NLP techniques and cosine similarity.

# 🗂️ Dataset
  ### tmdb_5000_movies.csv.
  ### tmdb_5000_credits.csv
   
# 🏗️ Project Structure

 movie-recommender-system/
│── data/
│ ├── tmdb_5000_movies.csv
│ ├── tmdb_5000_credits.csv
│
│── notebook/
│ ├── movie_recommender.ipynb
│
│── src/
│ ├── model.py
│ ├── utils.py
│
│── app/
│ ├── app.py (Streamlit UI)
│
│── pickle/
│ ├── movie_list.pkl
│ ├── similarity.pkl
│
│── README.md

# 📘 Requirements
 requirements.txt should include:
 pandas
numpy
scikit-learn
streamlit
pickle-mixin
requests



# 📦 Installation
# 1️⃣ Clone the repository
git clone https://github.com/your-username/movie-recommendation-system.git
cd movie-recommendation-system

# 2️⃣ Create a virtual environment

  python -m venv venv
venv\Scripts\activate     # Windows
source venv/bin/activate  # Mac/Linux

# 3️⃣ Install dependencies
 pip install -r requirements.txt

 # 💻 Streamlit UI (Optional)
 streamlit run app/app.py

# 📈 Results

Recommends top 5 most similar movies

High accuracy for movies with strong metadata (genres, cast, keywords)

Lightweight & fast








